# ECS CDK

This is a demonstration of how to launch cloud components such as ecs services using the aws cdk

The `cdk.json` file tells the CDK Toolkit how to execute your app.

## Getting Started

You need the following prerequisites:

- Node >= v14.00
- Npm >= v6.00
- Typescript

### Deploying Components

- Synthesize the code into an AWS CloudFormation template using the the cdk synth command.

```bash
cdk synth
```

- Bootstrap Resources

```bash
cdk bootstrap
```

- Deploy the stack by running the following command in the terminal:

```bash
cdk deploy
```

The terminal shows the steps AWS CloudFormation uses to deploy your App.  

Deploy times might vary.

> When the deployment is complete, in the Outputs section, press Ctrl and click to open the load balancer URL and display the sample application page.
> Log in to the AWS Management Console and search for CloudFormation. You should the deployed stack there

To avoid unexpected AWS charges, remove the newly created AWS CDK stack.

To remove all resources created in the stack, run the following command in the terminal:

```bash
cdk destroy
```

## Useful commands

- `npm run build`   compile typescript to js
- `npm run watch`   watch for changes and compile
- `npm run test`    perform the jest unit tests
- `cdk deploy`      deploy this stack to your default AWS account/region
- `cdk diff`        compare deployed stack with current state
- `cdk synth`       emits the synthesized CloudFormation template
