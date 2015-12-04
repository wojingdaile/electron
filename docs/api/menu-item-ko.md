# menu-item

## Class: MenuItem

### new MenuItem(options)

* `options` Object
  * `click` Function - �޴� �������� Ŭ���� �� ȣ��Ǵ� �ݹ��Լ�
  * `selector` String - First Responder�� Ŭ���� �� ȣ�� �Ǵ� ������ (OS X ����)
  * `type` String - `MenuItem`�� Ÿ�� `normal`, `separator`, `submenu`, `checkbox` �Ǵ� `radio` ��밡��
  * `label` String
  * `sublabel` String
  * `accelerator` [Accelerator](accelerator.md)
  * `icon` [NativeImage](native-image.md)
  * `enabled` Boolean
  * `visible` Boolean
  * `checked` Boolean
  * `submenu` Menu - �����޴��� �����մϴ�. `type`�� `submenu`�� ��� �ݵ�� �����ؾ��մϴ�. �Ϲ� �޴� �������� ��� ������ �� �ֽ��ϴ�.     
  * `id` String - ���� �޴� �����ۿ� ���� ����Ű�� �����մϴ�. �� Ű�� ���� `position` �ɼǿ��� ����� �� �ֽ��ϴ�.
  * `position` String - �̸� ������ `id`�� �̿��Ͽ� �޴� �������� ��ġ�� �����ϰ� �����մϴ�.
