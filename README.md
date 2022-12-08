## :warning: Deprecation notice
> This repository has been archived and is no longer maintained.

# Date Picker Custom Element Sample for Kentico Kontent

This is a [custom element](https://kontent.ai/learn/tutorials/develop-apps/integrate/content-editing-extensions) for [Kentico Kontent](https://kontent.ai) that allows users to use the jQuery UI date picker to select a date.

![Screenshot of custom element](DatePicker.gif)

## Setup

1. Deploy the code to a secure public host
    * See [deploying section](#Deploying) for a really quick option
1. Follow the instructions in the [custom elements documentation](https://kontent.ai/learn/tutorials/develop-apps/integrate/content-editing-extensions#a-displaying-your-custom-editor-in-kontent) to add the element to a content model.
    * The `Hosted code URL` is where you deployed to in step 1
    * Pass any optional parameters as directing in the [JSON Parameters configuration](#json-parameters) section of this readme.

## Deploying

Netlify has made this easy. If you click the deploy button below, it will guide you through the process of deploying it to Netlify and leave you with a copy of the repository in your GitHub account as well.

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/Kentico/kontent-custom-element-sample-date-picker)

## JSON Parameters

You can specify the format of the saved value by setting the optional `dateFormat` property in the JSON parameters:

```Json
{
  "dateFormat": "dd/mm/yy"
}
```

## Saved Value

The value is saved as a string representing the selected date as a string formatted according to the

## Contributors

Originally contributed by [@matus666](https://github.com/matus666/)
