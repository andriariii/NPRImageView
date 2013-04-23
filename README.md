## NPRImageView

Instagram-like UIImageView subclass. Progress view and activity view appear during image download. Support memory and disk caching. Inspired by [FXImageView](https://github.com/nicklockwood/FXImageView) and [Tapku](https://github.com/devinross/tapkulibrary)'s TKImageCache. Using AFNetworking.

## Requirement

1. [AFNetworking](https://github.com/AFNetworking/AFNetworking)
2. [libextobjc](https://github.com/jspahrsummers/libextobjc)

## After clone

    git submodule update --init --recursive

## How to use

1. Import files inside Class folder to your project.
2. Add AFNetworking to your project.
3. Add EXTScope.h, EXTScope.m, and metamacros.h from libextobjc to your project.
4. Simply call `setImageWithContentsOfURL:placeholderImage:` method.

## License
NPRImageView is available under the MIT license. See the License.txt file for more info.