# Spanish Messages for React-Admin

Spanish Messages for React-Admin, the frontend framework for building admin applications on top of REST/GraphQL services.

# Installation

```
npm install --save @spectrum/ra-language-spanish
```

# Usage

```
import spanishMessages from '@spectrum/ra-language-spanish';
import polyglotI18nProvider from 'ra-i18n-polyglot';

const messages = {
    'es': spanishMessages,
};
const i18nProvider = polyglotI18nProvider(locale => messages[locale]);

<Admin locale="es" i18nProvider={i18nProvider}>
  ...
</Admin>
```

# License

This translation is licensed under the MIT License.
