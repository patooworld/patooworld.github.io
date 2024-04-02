# PWA Starter

[**Straight to Full Documentation**](https://docs.pwabuilder.com/#/starter/quick-start)

The PWABuilder pwa-starter is our opinionated, best practices, production tested starter that we use to build all of our PWAs, including [PWABuilder itself](https://blog.pwabuilder.com/posts/introducing-the-brand-new-pwa-builder/)! The pwa-starter is a starter codebase, just like create-react-app or the Angular CLI can generate, that uses the PWABuilder team&#39;s preferred front-end tech stack. We also have a CLI tool to allow you to create a PWA template from the command line.

## Jump Right In

Install the PWABuilder CLI:

`npm i -g @pwabuilder/cli`

And create a new app with this command:

`pwa create`

And start your app locally with:

`pwa start`

And that's it! Good luck on your Progressive Web App adventure!

## More Info

[![Get started with the pwa-starter!](https://img.youtube.com/vi/u3pWKpmic_k/0.jpg)](https://www.youtube.com/watch?v=u3pWKpmic_k)

With it you get an app that:
- Has no build system to set up and no boilerplate code to add. Everything is included out of the box.
- Has a Service Worker system using [Workbox](https://developers.google.com/web/tools/workbox/)
- Scores close to 100 on Lighthouse out of the box
- Has everything needed to be installable in the browser
- Is ready to be package for the app stores using [PWABuilder](https://www.pwabuilder.com)
- Uses the [Azure Static Web Apps CLI](https://azure.github.io/static-web-apps-cli) which enables emulating your production environment locally, and gets you ready for deploying to Azure Static Web Apps!

and all with just a few button clicks 😊.

<p>The AWS Toolkit lets you interact with AWS directly from VS Code. Ready to install? See <a href="#getting-started">Getting Started</a>.</p>
<h2><a href="https://aws.amazon.com/q/">Amazon Q (preview)</a></h2>
<p>Amazon Q is your conversational assistant for building, maintaining, and transforming applications. Amazon Q can do the following from the IDE:</p>
<ul>
<li>Answer questions about AWS</li>
<li>Answer questions about general programming concepts</li>
<li>Explain what a line of code or code function does</li>
<li>Write unit tests and code</li>
<li>Debug and fix code</li>
<li>Refactor code</li>
</ul>
<p><img src="https://github.com/aws/aws-toolkit-vscode/raw/HEAD/docs/marketplace/vscode/codewhispererChat.gif" alt="Amazon Q"></p>
<h2><a href="https://aws.amazon.com/codewhisperer/">Amazon CodeWhisperer</a></h2>
<p>An AI powered productivity tool for the IDE.</p>
<ul>
<li><strong>Real-time code suggestions</strong> - automatic code recommendations in 15+ languages, now including infrastructure as code (CloudFormation, AWS CDK, and Terraform)</li>
<li><strong>Optimized for use with AWS services</strong> - code suggestions are optimized for AWS APIs including Amazon Elastic Compute Cloud (Amazon EC2), AWS Lambda, and Amazon Simple Storage Service (Amazon S3)</li>
<li><strong>Built-in security scans</strong> - Scan your code to detect hard-to-find vulnerabilities and get code suggestions to remediate them immediately</li>
</ul>
<p><img src="https://github.com/aws/aws-toolkit-vscode/raw/HEAD/docs/marketplace/vscode/codewhisperer.gif" alt="CodeWhisperer"></p>
<h2><a href="https://aws.amazon.com/application-composer/">Application Composer</a></h2>
<p>AWS Application Composer maintains a real-time visual representation of your application architecture in sync with your IaC. Changes to the architecture—such as adding new resources or changing service configuration—are reflected in the IaC artifacts, and vice versa.</p>
<ul>
<li>Visually compose modern applications from 1,000+ AWS CloudFormation resources with little guesswork.</li>
<li>Use the right tool for the task, including visual, code, or generative AI powered code suggestions in your IDE.</li>
<li>Integrate with Workflow Studio to visually orchestrate over 220 AWS services or public http endpoints with Step Functions workflows.</li>
</ul>
<p><img src="https://github.com/aws/aws-toolkit-vscode/raw/HEAD/docs/marketplace/vscode/appComposer.gif" alt="Application Composer"></p>
<h2><a href="https://codecatalyst.aws/explore"><strong>Amazon CodeCatalyst</strong></a></h2>
<p>Unified software development service to quickly build and deliver applications on AWS.</p>
<p><strong>Dev Environments</strong> - launch VS Code in a cloud development environment, available on-demand in the cloud and automatically created with branch code and consistent project settings, providing faster setup, development, and testing</p>
<p><img src="https://github.com/aws/aws-toolkit-vscode/raw/HEAD/docs/marketplace/vscode/CC_dev_env.gif" alt="CodeCatalyst"></p>
<h2>View, modify, and deploy AWS resources</h2>
<p><strong>Multiple AWS accounts and regions</strong> - access AWS resources across your accounts and regions</p>
<p><img src="https://github.com/aws/aws-toolkit-vscode/raw/HEAD/docs/marketplace/vscode/creds.gif" alt="creds"></p>
<p><strong>S3 support</strong> - view, create, and edit S3 buckets, folders, and files</p>
<p><img src="https://github.com/aws/aws-toolkit-vscode/raw/HEAD/docs/marketplace/vscode/S3.gif" alt="S3"></p>
<p><strong>Lambda</strong> - download &amp; upload Lambda functions</p>
<p><img src="https://github.com/aws/aws-toolkit-vscode/raw/HEAD/docs/marketplace/vscode/download-Lambda.gif" alt="download-Lambda"></p>
<h2>Troubleshoot AWS from the IDE</h2>
<p><strong>Lambda</strong> - step-through AWS Lambda functions using the VS Code debugger</p>
<p><img src="https://github.com/aws/aws-toolkit-vscode/raw/HEAD/docs/marketplace/vscode/Lambda_step_through_debugging.gif" alt="Lambda_step_through_debugging"></p>
<p><strong>CloudWatch</strong> - find logs generated by your AWS resources</p>
<p><img src="https://github.com/aws/aws-toolkit-vscode/raw/HEAD/docs/marketplace/vscode/cw_logs.gif" alt="cw_logs"></p>
<p><strong>ECS</strong> - execute commands against running ECS containers (or open a terminal)</p>
<p><img src="https://github.com/aws/aws-toolkit-vscode/raw/HEAD/docs/marketplace/vscode/ecs-terminal.gif" alt="ecs-terminal"></p>
<h2>More features</h2>
<ul>
<li><strong>Redshift</strong> - view database objects and run SQL queries in a notebook interface</li>
<li><strong>Step Functions</strong> - work with asl files and render state machine visuals</li>
<li><strong>CloudFormation</strong> - view CloudFormation stacks</li>
<li><strong>API Gateway</strong> - invoke an API gateway endpoint</li>
<li><strong>S3</strong> - view and create S3 folders and buckets, download and upload files, and edit supported files</li>
</ul>
<p>For a full list of features, visit <a href="https://docs.aws.amazon.com/toolkit-for-vscode/latest/userguide/working-with-aws.html">our documentation</a>.</p>
<h2>Getting Started</h2>
<ol>
<li>Open the AWS Toolkit extension</li>
<li>Add AWS credentials<ol>
<li><strong>AWS resources</strong> - connect using IAM credentials or IAM Identity Center (formerly SSO)</li>
<li><strong>CodeWhisperer</strong> - connect using AWS Builder ID or IAM Identity Center (formerly SSO)</li>
<li><strong>CodeCatalyst</strong> - connect using AWS Builder ID</li>
</ol>
</li>
</ol>
<p><img src="https://github.com/aws/aws-toolkit-vscode/raw/HEAD/docs/marketplace/vscode/getting-started.gif" alt="getting-started"></p>
<h2>Troubleshooting</h2>
<p>Submit bug reports and feature requests <a href="https://github.com/aws/aws-toolkit-vscode/issues/new/choose">on our Github repository</a>.</p>
