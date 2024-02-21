# pdf-chem-highlighter

This is a fork of [agentcooper/react-pdf-highlighter](https://github.com/agentcooper/react-pdf-highlighter/)

The idea is to get annotations of chemical substances and chemical roles from a separate LLM-based webservice for any uplodaded PDF file (e.g. research paper). The PDF file will be rendered and any roles or chemicals will be marked inside of the text.
If a found chemical substance or role corresponds to an entry in the Chebi ontology, we will provide a hyperlink to Chebi.

### Example

To run the example app locally:

```
npm install
npm start
```

Create React App example is available in [`./create-react-app-example`](https://github.com/agentcooper/react-pdf-highlighter/tree/main/create-react-app-example). Make sure to run `npm install` there as well
