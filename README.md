<a href="https://lexi-ai-one.vercel.app/">
  <img alt="LexiAI: Advanced AI-Powered Legal Analysis Platform" src="app/(chat)/opengraph-image.png">
  <h1 align="center">LexiAI</h1>
</a>

<p align="center">
  An AI-powered legal document analysis platform that simplifies complex legal documents and provides intelligent insights.
</p>

<p align="center">
  <a href="#features"><strong>Features</strong></a> ·
  <a href="#ai-capabilities"><strong>AI Capabilities</strong></a> ·
  <a href="#deploy-lexiai"><strong>Deploy LexiAI</strong></a> ·
  <a href="#local-development"><strong>Local Development</strong></a>
</p>
<br/>

## Features

- **Legal Document Analysis**
  - Parse and analyze complex legal documents instantly
  - Extract key terms, commitments, and potential risks
  - Compare multiple contracts side-by-side with difference highlighting
- **AI-Powered Legal Assistance**
  - Get plain-language explanations of legal jargon
  - Receive suggested modifications to contract language
  - Identify missing clauses and potential legal vulnerabilities
- **Document Management**
  - Organize legal documents in customizable workspaces
  - Track document versions and revisions
  - Collaborate with team members on document review
- **Interactive Chat Interface**
  - Ask questions about your legal documents in natural language
  - Receive contextual answers with citations to specific document sections
  - Save important insights and export summaries

## Technical Foundation

- **Modern Web Architecture**
  - [Next.js](https://nextjs.org) App Router for optimal performance and SEO
  - React Server Components for reduced client-side JavaScript
  - Server Actions for secure, server-side operations
- **Advanced AI Integration**
  - Custom-tuned legal language models
  - [AI SDK](https://sdk.vercel.ai/docs) for unified API interactions with multiple LLMs
  - Specialized legal prompt engineering for accurate document analysis
- **Polished User Experience**
  - Responsive design built with [Tailwind CSS](https://tailwindcss.com)
  - Accessible UI components from [shadcn/ui](https://ui.shadcn.com)
  - Intuitive document annotation and navigation
- **Enterprise-Grade Infrastructure**
  - [Vercel Postgres](https://vercel.com/storage/postgres) for reliable data persistence
  - [Vercel Blob](https://vercel.com/storage/blob) for efficient document storage
  - End-to-end encryption for sensitive legal documents

## AI Capabilities

LexiAI combines multiple specialized AI models to deliver comprehensive legal analysis:

- **Document Processing**
  - Semantic parsing of legal documents with structure recognition
  - Table and form extraction with relational understanding
  - Multi-language support for international legal documents

- **Legal Analysis**
  - Jurisdiction-specific legal term recognition
  - Obligation and liability extraction
  - Compliance assessment against regulatory frameworks

- **Security & Privacy**
  - All document processing happens server-side
  - Data retention policies configurable by organization
  - Privacy-preserving AI analysis with minimal data exposure

## Deploy LexiAI

You can deploy your own instance of LexiAI to Vercel with one click:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Flexiai%2Flexiai-platform&env=AUTH_SECRET,AI_API_KEY&envDescription=Secure%20keys%20for%20authentication%20and%20AI%20access&envLink=https%3A%2F%2Fdocs.lexiai.app%2Fdeployment%2Fenvironment-variables&project-name=lexiai-instance&repository-name=lexiai-platform&demo-title=LexiAI%20Platform&demo-description=AI-powered%20legal%20document%20analysis%20platform%20that%20simplifies%20complex%20legal%20documents&demo-url=https%3A%2F%2Flexiai.app&demo-image=https%3A%2F%2Flexiai.app%2Fimages%2Fsharing-image.png)

## Local Development

To run LexiAI locally, you'll need to configure the environment variables listed in `.env.example`. We recommend using Vercel's environment management:

1. Install Vercel CLI: `npm i -g vercel`
2. Link your local project: `vercel link`
3. Pull environment variables: `vercel env pull`

Then start the development server:

```bash
pnpm install
pnpm dev
```

Navigate to [localhost:3000](http://localhost:3000/) to see LexiAI running locally.

## Enterprise Solutions

LexiAI offers additional features for enterprise customers, including:

- **Custom LLM Training** - Train models on your organization's legal corpus
- **API Integration** - Connect with existing legal document management systems
- **Advanced Compliance** - Specialized modules for GDPR, CCPA, and industry regulations
- **White-labeling** - Deploy with your organization's branding

Contact us at [enterprise@lexiai.app](mailto:enterprise@lexiai.app) to learn more.

## Contributing

We welcome contributions to LexiAI! See our [contributing guidelines](CONTRIBUTING.md) for more information on how to get involved.

## License

LexiAI is licensed under the [MIT License](LICENSE).