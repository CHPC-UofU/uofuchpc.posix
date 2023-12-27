# Ansible Collection - uofuchpc.posix

An Ansible Collection extending `ansible.posix`.

## Supported Versions of Ansible

This collection has been tested against following Ansible versions: `>=2.15`.

## Included content
<!--start collection content-->
### Modules
Name | Description
--- | ---
[uofuchpc.posix.firewalld](https://github.com/CHPC-UofU/uofuchpc.posix/tree/main/docs/uofuchpc.posix.firewalld_module.rst)|Manage firewalld.
<!--end collection content-->

## Installing this Collection

You can locally build and install the `uofuchpc.posix` collection with the Ansible Galaxy CLI:

```console
$ mkdir ./build
$ ansible-galaxy collection build -f . --output-path build
...
$ ansible-galaxy collection install build/uofuchpc-posix-X.X.X.tar.gz --force
...
```

You can also include it in a `requirements.yml` file and install it with `ansible-galaxy collection install -r requirements.yml`, using the format:

```yaml
collections:
  - name: https://github.com/CHPC-UofU/uofuchpc.posix/releases/download/v<release>/uofuchpc-posix-<release>.tar.gz
    type: url
```

## Using this Collection

See [Ansible Using collections](https://docs.ansible.com/ansible/latest/user_guide/collections_using.html) for more details.

## More Information

* [Creating a Module](https://docs.ansible.com/ansible/latest/dev_guide/developing_modules_general.html#creating-a-module)

## Testing

XXXX
