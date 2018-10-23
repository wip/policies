# Privacy Policy

Gregor Martynus ("Me", "Myself", and "I") built WIP (the "app") as an Open Source GitHub App. This service is provided by myself and is intended for use as is.

This page is used to inform users ("you") regarding my policies with the collection, use, and disclosure of personal information if anyone decided to use this service.

If you choose to use the app, then you agree to the collection and use of information in relation to this policy. The collected information is required for the service to work. It is neither stored nor shared with 3rd parties.

## Information collection and use

When installing the the app you grant it access to the following three scopes

1. **Read & write access to [pull requests](https://developer.github.com/v3/apps/permissions/#permission-on-statuses)**

   The app looks for terms in the pull request title, body, labels and commit messages. It requires write access to amend a "pending" status for a pull request by amending the body with `@wip ready for review` comment.

2. **Read & write access to [checks](https://developer.github.com/v3/apps/permissions/#permission-on-checks)**

   The app uses checks to explain why the status for your pull request has been set to pending or success.

3. **Read access to [single file](https://developer.github.com/v3/apps/permissions/#permission-on-single-file)**: `.github/wip.yml`

   The app can be configured by created a `.github/wip.yml` file. The app does not have access to any other files in your repository.

The app receives [CheckRun](https://developer.github.com/v3/activity/events/types/#checkrunevent) and [PullRequest](https://developer.github.com/v3/activity/events/types/#pullrequestevent) events from GitHub, but any data not required for the functionality of the app is discarded.

## Sharing of data with 3rd party services

The app is hosted on [Zeit’s now](https://zeit.co/now). No user data is persisted besides a temporary storage of log files for less than 30 days.

For the purpose of monitoring and analytics, log data is shared with [LogDNA](https://logdna.com/) ([LogDNA Privacy Notice](https://logdna.com/privacy-shield/)) for live monitoring and [Amazon S3](https://aws.amazon.com/s3/) for archiving ([Amazon Web Services Privacy Notice](https://aws.amazon.com/privacy/)). Log data is retained for 1 year as recommended by GitHub Marketplace.

For the purpose of error tracking, error stacks are shared with [Sentry](https://sentry.io/) ([Privacy notice](https://sentry.io/privacy/)).

## Security

I value your trust in providing your personal information, thus I am striving to use commercially acceptable means of protecting it. But remember that no method of transmission over the internet, or method of electronic storage is 100% secure and reliable, and I cannot guarantee its absolute security.

## Changes to this privacy policy

I may update this privacy policy from time to time. Thus, you are advised to review this page periodically for any changes. I will notify you of any changes by creating a pull request on this repository and leaving it open for at least 14 days to give time for you to raise any concerns. These changes are effective immediately after they are merged into the main branch.

## Contact me

If you have any questions or suggestions about my Privacy Policy, do not hesitate to contact me at `wip@martynus.net`.
