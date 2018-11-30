# Packer Images

Here, we will learn how Packer creates vm images. Let us look at the contents of the .json file:

```builders``` This initial will tell the machine to build the specified image in the following block.
```type: google.compute``` Our type is google compute, since we are building an image in Google's cloud environment.
```account_file``` This is the key that was downloaded on to your host machine. Store it in a file and provide its source.
```project_id``` This is your project ID.
```source_image_family``` Your operating system.
```ssh_username``` The username for your user.
```zone``` The zone where you vm is spun up.
