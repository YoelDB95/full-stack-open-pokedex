To create the app with Python ecosystem, we can use black, that is a code formatter that ensures consistent code formatting standards.

For testing, pytest is a widely used tool that will allow us to write simple and scalable test cases.
It integrates well with CI pipelines to run tests automatically every time changes are made to the codebase.

Building the Python packages can be automated using tools like setuptools or poetry. These tools help in creating distributable packages and managing dependencies. Additionally, we can use Docker to create reproducible build environments that ensure consistency across different machines.

Besides Github Actions and Jenkins, there are multiple alternatives to consider in seting up the CI. We can use GitLab CI/CD that provides a platform for running pipelines directly alongside your GitLab repositories. It is available in both self-hosted and managed SaaS forms and integrates well with other GitLab components and cloud deployment environments. GitLab CI/CD can directly connect to Kubernetes clusters to run jobs and launch apps. Other platform we can use is Azure DevOps, a comprehensive set of DevOps tools that includes CI/CD capabilities. It integrates seamlessly with Azure services and supports a wide range of development and deployment scenarios.

Choosing between a self-hosted or cloud-based environment depends on several factors, including security, environmental impact, control, and cost-effectiveness.

Cloud computing systems are significantly better secured than self-hosting services, as they use nix-based systems (Unix or Linux) which are less vulnerable to virus attacks than traditional computer networks.
However, self-hosted solutions offer more control over data and infrastructure, allowing for customization and integration across different systems.
Additionally, self-hosting can be more cost-effective in the long term due to the ability to tailor costs to specific needs and avoid vendor lock-in.
