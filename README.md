# Vue-next 中文文档翻译项目

> 使用声明：鉴于个人英文水平有限，个别术语翻译可能不太准确，不代表最终版！建议大家去看英文版，或有能力的，可以发起PR，来修正该问题，我会尽快回应！谢谢！！

## 特性

- 支持i18n
- 同步官方英文文档
- 默认为中文文档

## 如何参与Vue 3 中文仓库项目+注意事项？

### 如何参与？

1. 然后clone 本仓库
```bash
git clone git@github.com:veaba/docs-next.git
```
  - 可以更新readme的 [进度](#进度) ，填写上你的Github账号，发起pr，以免重复翻译

2. 安装依赖
```bash
yarn # or npm install
```

3. 项目启动
```bash
yarn serve # or npm run serve
```

4. 翻译文档

5. 发起pr，会有专人记录


### 如何添加一个译者注释？
> 基本参考或者直接搬用原[cn.vuejs.org](https://github.com/vuejs/cn.vuejs.org)

到需要注释的地方
```md
安装<sup>[[1]](#footnote-1)</sup>
```
在该注释文档的底部

```md
<small>**译者注**<a id="footnote-1"></a>[1] 对于中国大陆
用户，建议将 NPM 源设置为[国内的镜像](https://npm.taobao.org/)，可以
大幅提升安装速度。</small>
```

### 存在争议的翻译

如果发现某些段落有疑虑，不顺畅的，可以打个记号，以让其他人协助完成。

|记录|翻译人|校验人|状态|
|----|----|----|----|
|[[argue-1]](/src/guide/installation.md#argue-1)||-||
|[[argue-2]](/src/guide/reactivity-computed-watchers.md#argue-2)|-|||
|[[argue-3]](/src/guide/reactivity-computed-watchers.md#argue-3)|-|||
||-|||
||-|||

### 翻译规范

- [术语翻译约定.md](https://github.com/vuejs/cn.vuejs.org/wiki)



## 进度&贡献

|模块章节|翻译人|校验人|状态|
|----|----|----|----|
|[/guide/installation.md](/src/guide/installation.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/introduction.md](/src/guide/introduction.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/instance.md](/src/guide/instance.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/template-syntax.md](/src/guide/template-syntax.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/computed.md](/src/guide/computed.md)|[@veaba](https://github.com/veaba)||完成翻译|
|[/guide/class-and-style.md](/src/guide/class-and-style.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/conditional.md](/src/guide/conditional.md)|[@veaba](https://github.com/veaba)|||
|[/guide/list.md](/src/guide/list.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/events.md](/src/guide/events.md)|[@veaba](https://github.com/veaba)||完成翻译|
|[/guide/forms.md](/src/guide/forms.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/component-basic.md](/src/guide/component-basics.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|-|-|-|-|
|[/guide/component-registration.md](/src/guide/component-registration.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/component-props.md](/src/guide/component-props.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/component-custom-events.md](/src/guide/component-custom-events.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/component-slots.md](/src/guide/component-slots.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/component-provide-inject.md](/src/guide/component-provide-inject.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/component-dynamic-async.md](/src/guide/component-dynamic-async.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/component-template-refs.md](/src/guide/component-template-refs.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/component-edge-cases.md](/src/guide/component-edge-cases.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|-|-|-|-|
|[/guide/transitions-overview.md](/src/guide/transitions-overview.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/transitions-enterleave.md](/src/guide/transitions-enterleave.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/transitions-list.md](/src/guide/transitions-list.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/transitions-state.md](/src/guide/transitions-state.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|-|-|-|-|
|[/guide/mixins.md](/src/guide/mixins.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/custom-directive.md](/src/guide/custom-directive.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/teleport.md](/src/guide/teleport.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/render-function.md](/src/guide/render-function.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/plugins.md](/src/guide/plugins.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|-|-|-|-|
|[/guide/reactivity.md](/src/guide/reactivity.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/reactivity-fundamentals.md](/src/guide/reactivity-fundamentals.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/reactivity-computed-watchers.md](/src/guide/reactivity-computed-watchers.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|-|-|-|-|
|[/guide/composition-api-introduction.md](/src/guide/composition-api-introduction.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/composition-api-setup.md](/src/guide/composition-api-setup.md)|[@veaba](https://github.com/veaba)|-|完成翻译||
|[/guide/composition-api-lifecycle-hooks.md](/src/guide/composition-api-lifecycle-hooks.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/composition-api-provide-inject.md](/src/guide/composition-api-provide-inject.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/composition-api-template-refs.md](/src/guide/composition-api-template-refs.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|-|-|-|-|
|[/guide/optimizations.md](/src/guide/optimizations.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/change-detection.md](/src/guide/change-detection.md)|[from Vue 2](https://cn.vuejs.org/about.html))|-|完成翻译，应用自Vue2|
|-|-|-|-|
|[/guide/single-file-component.md](/src/guide/single-file-component.md)| [from Vue 2](https://cn.vuejs.org/about.html)|-|完成翻译，应用自Vue2|
|[/guide/testing.md](/src/guide/testing.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|-|-|-|-|
|[/guide/routing.md](/src/guide/routing.md)|[from Vue 2](https://cn.vuejs.org/about.html)|-|完成翻译，应用自Vue2|
|[/guide/state-management.md](/src/guide/state-management.md)|[from Vue 2](https://cn.vuejs.org/about.html)|-|完成翻译，应用自Vue2|
|[/guide/ssr.md](/src/guide/ssr.md)|[from Vue 2](https://cn.vuejs.org/about.html)|-|完成翻译，应用自Vue2|
|-|-|-|-|
|[/guide/a11y-basics.md](/src/guide/a11y-basics.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/a11y-semantics.md](/src/guide/a11y-semantics.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/a11y-standards.md](/src/guide/a11y-standards.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|[/guide/a11y-resources.md](/src/guide/a11y-resources.md)|[@veaba](https://github.com/veaba)|-|完成翻译|
|-|-|-|-|
|[/migration/introduction.md](/src/migration/introduction.md)|[@veaba](https://github.com/veaba)|-|- 翻译完成|
|[/migration/async-components.md](/src/migration/async-components.md)|[@veaba](https://github.com/veaba)|-|- 翻译完成|
|[/migration/attribute-coercion.md](/src/migration/attribute-coercion.md)|[@veaba](https://github.com/veaba)|-|- 翻译完成|
|[/migration/custom-directives.md](/src/migration/custom-directives.md)|[@veaba](https://github.com/veaba)|-|- 翻译完成|
|[/migration/custom-elements-interop.md](/src/migration/custom-elements-interop.md)|[@veaba](https://github.com/veaba)|-|- 翻译完成|
|[/migration/data-option.md](/src/migration/data-option.md)|[@veaba](https://github.com/veaba)|-|- 翻译完成|
|[/migration/events-api.md](/src/migration/events-api.md)|[@veaba](https://github.com/veaba)|-|- 翻译完成|
|[/migration/filters.md](/src/migration/filters.md)|[@veaba](https://github.com/veaba)|-|- 翻译完成|
|[/migration/fragments.md](/src/migration/fragments.md)|[@veaba](https://github.com/veaba)|-|- 翻译完成|
|[/migration/functional-components.md](/src/migration/functional-components.md)|[@veaba](https://github.com/veaba)|-|- 翻译完成|
|[/migration/global-api.md](/src/migration/global-api.md)|[@veaba](https://github.com/veaba)|-|- 翻译完成|
|[/migration/global-api-treashaking.md](/src/migration/global-api-treashaking.md)|[@veaba](https://github.com/veaba)|-|- 翻译完成|
|[/migration/inline-template-modifiers.md](/src/migration/inline-template-modifiers.md)|[@veaba](https://github.com/veaba)|-|- 翻译完成|
|[/migration/keycode-mofifiers.md](/src/migration/keycode-mofifiers.md)|[@veaba](https://github.com/veaba)|-|- 翻译完成|
|[/migration/render-function-api.md](/src/migration/render-function-api.md)|[@veaba](https://github.com/veaba)|-|- 翻译完成|
|[/migration/slots-unification.md](/src/migration/slots-unification.md)|[@veaba](https://github.com/veaba)|-|- 翻译完成|
|[/migration/v-model.md](/src/migration/v-model.md)|[@veaba](https://github.com/veaba)|-|- 翻译完成|
|-|-|-|-|
|[contributing/writing-guide.md](/src/guide/contributing/writing-guide.md)|[@veaba](https://github.com/veaba)|-|- 翻译完成|
|[contributing/doc-style-guide.md](/src/guide/contributing/doc-style-guide.md)|[@veaba](https://github.com/veaba)|-|- 翻译完成|
|[contributing/translations.md](/src/guide/contributing/translations.md)|[@veaba](https://github.com/veaba)|-|- 翻译完成|
|-|-|-|-|
|[/api/application-config.md](/src/api/application-config.md)|[from Vue 2](https://cn.vuejs.org/about.html)|-|完成翻译，应用自Vue2|
|[/api/application-api.md](/src/api/application-api.md))|[@veaba](https://github.com/veaba)|-|- 翻译完成|
|[/api/global-api.md](/src/api/global-api.md)|[@veaba](https://github.com/veaba)|-|- 翻译完成|
|-|-|-|-|
|[/api/options-data.md](/src/api/options-data.md)|<p>[from Vue 2](https://cn.vuejs.org/about.html)</p1> <p>[@veaba](https://github.com/veaba)</p>|-|完成翻译|
|[/api/options-dom.md](/src/api/options-dom.md)|<p>[from Vue 2](https://cn.vuejs.org/about.html)</p1> <p>[@veaba](https://github.com/veaba)</p>|-|完成翻译|
|[/api/options-lifecycle-hooks.md](/src/api/options-lifecycle-hooks.md)|<p>[from Vue 2](https://cn.vuejs.org/about.html)</p1> <p>[@veaba](https://github.com/veaba)</p>|-|完成翻译|
|[/api/options-assets.md](/src/api/options-assets.md)|<p>[from Vue 2](https://cn.vuejs.org/about.html)</p1> <p>[@veaba](https://github.com/veaba)</p>|-|完成翻译|
|[/api/options-composition.md](/src/api/options-composition.md)||-||
|[/api/options-misc.md](/src/api/options-misc.md)||-||
|-|-|-|-|
|[/api/instance-properties.md](/src/api/instance-properties.md)||-||
|[/api/instance-methods.md](/src/api/instance-methods.md)||-||
|[/api/directives.md](/src/api/directives.md)||-||
|[/api/special-attributes.md](/src/api/special-attributes.md)||-||
|[/api/built-in-components.md](/src/api/built-in-components.md)||-||
|-|-|-|-|
|[/api/basic-reactivity.md](/src/api/basic-reactivity.md)||-||
|[/api/refs-api.md](/src/api/refs-api.md)||-||
|[/api/computed-watch-api.md](/src/api/computed-watch-api.md)||-||
|-|-|-|-|
|[/api/composition-api.md](/src/api/composition-api.md)||-||
|-|-|-|-|


## 引用与参考

- 原[vue2 中文文档.md](https://cn.vuejs.org)
- 原[vue 2 英文文档.md](https://vuejs.org)
- 原[vue 3 英文文档.md](https://v3.vuejs.org)


## Writing

See the [Vue Docs Writing Guide.md](https://v3.vuejs.org/guide/writing-guide.html) for our rules and recommendations on writing and maintaining documentation.

> The docs are in beta: The team is currently in the midst of changes and we are not ready for additional contributions yet. All content is subject to change. If you see a problem that you would like to bring to our attention, please [create an issue.md](https://github.com/vuejs/docs-next/issues/new) and we will get to it when we can. You may want to wait until the content is finalized, though.


## 部署

The site is automatically deployed when commits land in `master`, via [Netlify.md](https://www.netlify.com/).
