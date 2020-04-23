# VoliTemplates

templates for the dart package named [Voli](https://pub.dev/packages/voli)

## Folder and Template Format

```shell
# template folder format
+---template_name
|   |   template.yaml
|   |
|   \---files
|           main.dart

# Example

+---tdd
|   |   template.yaml
|   |
|   \---files
|           main.dart
```

```yaml

description: Description for your template



# yet to add these features
# dependencies:
#     yaml: ^2.2.0
#     path: ^1.7.0
#     args: ^1.6.0
#     http: ^0.12.0+4
# dev_dependencies:
#     voli:
  

# files:
#   folder/name_of_file: folder_in_template/name_of_file.file_extension

dirs:
# Use appropriate names for your 'folders'
  folder:
    sub_folder:
        folder_with_folders:
            - this_folder_does_not_have_child_folder
            - another_folder_does_not_have_child_folder
            - yet_another_folder_does_not_have_child_folder

        one_more_folder_with_folders:
        # practical names
            - state_management
            - pages
            - widgets

```
