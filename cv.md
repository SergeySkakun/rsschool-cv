# Sergey Skakun

## Contact Information

- **Discord**: delerium9059
- **Email**: sergeylearn116@gmail.com

## About Me

> _I want to find a decent job in a field that I like. I've loved computers and games since childhood. That's why I went to study to be a programmer. After that, I worked with computer cash registers and as a system administrator. Now I want to work in software development. To touch the other side and create something myself._

## Skills

- HTML
- CSS
- JavaScript
- ESLint
- Chrome Dev Tools
- Git
- Figma

## Code Examples

[Task](https://www.codewars.com/kata/515bb423de843ea99400000a)

```
class PaginationHelper {
	constructor(collection, itemsPerPage) {
    this.collection = collection;
    this.itemsPerPage = itemsPerPage;
	}

	itemCount() {
	  return this.collection.length;
	}

	pageCount() {
	  return Math.ceil(this.itemCount() / this.itemsPerPage);
	}

	pageItemCount(pageIndex) {
    const pageCount = this.pageCount() - 1;
    if (pageIndex < 0 || pageIndex > pageCount) {
      return -1;
    }

    if (pageIndex === pageCount) {
      return this.collection.length % this.itemsPerPage || this.itemsPerPage;
    }

    return this.itemsPerPage;
	}

	pageIndex(itemIndex) {
    if (itemIndex < 0 || itemIndex >= this.itemCount()) {
      return -1;
    }
	  return Math.floor(itemIndex / this.itemsPerPage);
	}
}
```
