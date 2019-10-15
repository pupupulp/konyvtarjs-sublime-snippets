# Konyvtar Sublime Snippets

A sublime snippet for KonyvtarJS package on NPM https://www.npmjs.com/package/konyvtar-js

## Documentation

### Table of Contents

- [Component](#component)
- [Store](#store)
- [Grid](#grid)
- [Combobox](#combobox)
- [Form](#form)
- [Button](#button)
- [Render](#render)
- [Ajax](#ajax)
- [Url](#url)
- [Task](#task)
- [Window](#window)

### Features

#### Component

+ **kcq** - ```Kony.component.query(queryString);```
+ **kcr** - ```Kony.component.reference(component, reference);```

#### Store

+ **ksc** - ```Kony.store.create(url, extraParams, component, autoLoad, pageSize);```
+ **kst** - ```Kony.store.tree(url, extraParams, component, autoLoad, folderSort);```
+ **ksl** - ```Kony.store.local(records);```

### Grid

+ **kgg** - ```Kony.grid.get(reference);```
+ **kgs** - ```Kony.grid.setup(reference, storeUrl, filters);```
+ **kgc** - ```Kony.grid.clear(reference);```
+ **kggs** - ```Kony.grid.getSelection(reference);```
+ **kgcs** - ```Kony.grid.clearSelection(reference);```
+ **kggst** - ```Kony.grid.getStore(reference);```
+ **kgr** - ```Kony.grid.reload(reference);```

    #### Render

    + **kgrd** - ```Kony.grid.render.default();```
    + **kgrqt** - ```Kony.grid.render.qTip();```
    + **kgrcc** - ```Kony.grid.render.checkColumn();```
    + **kgryn** - ```Kony.grid.render.yesNo();```
    + **kgrc** - ```Kony.grid.render.currency();```
    + **kgra** - ```Kony.grid.render.accurate();```
    + **kgrfd** - ```Kony.grid.render.fullDate();```
    + **kgrymd** - ```Kony.grid.render.ymdDate();```
    + **kgrdmy** - ```Kony.grid.render.dmyDate();```
    + **kgrmdy** - ```Kony.grid.render.mdyDate();```

### Combobox 

+ **kcg** - ```Kony.combobox.get(reference);```
+ **kcs** - ```Kony.combobox.setup(reference, storeUrl, filters);```
+ **kcgrid** - ```Kony.combobox.getRecordById(reference, id);```

### Form 

+ **kfg** - ```Kony.form.get(reference);```
+ **kfgv** - ```Kony.form.getValues(reference);```
+ **kflr** - ```Kony.form.loadRecord(reference, record);```
+ **kfsro** - ```Kony.form.setReadOnly(reference, isReadOnly);```
+ **kfc** - ```Kony.form.clear(reference);```
+ **kfiv** - ```Kony.form.isValid(reference);```
+ **kfgif** - ```Kony.form.getInvalidFields(reference);```

## About

### Contributing

Pull requests and stars are always welcome. For bugs and feature requests, please [create an issue](https://github.com/pupupulp/konyvtarjs-sublime-snippets/issues/new).

### Related Projects

You might want to checkout these projects:

- [NchikotaJS](https://github.com/pupupulp/nchikota-js) - An opensource tech stack composed of ExpressJS, NodeJS, ExtJS.
- [PasserelleJS](https://github.com/pupupulp/passerelle-js) - An opensource API gateway built with ExpressJS.
- [KonyvtarJS](https://github.com/pupupulp/konyvtar-js) - An opensource library/package of code wrappers for ExtJS 6.2.0 GPL.

### Contributors

### Author

**Eagan Martin**
- [Github](https://github.com/pupupulp)
- [LinkedIn]()

### License

Copyright © 2019, [Eagan Martin](https://github.com/pupupulp). Release under the [MIT License](https://github.com/pupupulp/konyvtarjs-sublime-snippets/blob/master/LICENSE)