# packaged-cli-diagnostics
Python CLI tool for deterministic developer-environment diagnostics with JSON/text reports and automated tests.


Developer Environment Health Report
===================================
Status: unhealthy
Exit code: 1

[PASS] python: Python 3.13.1

[PASS] disk_space: 1.91 GB free

[PASS] environment: All required environment variables are present
  required: []
  missing: []

[FAIL] developer_tools: Missing tools: docker, git, node, npm, pip, python
  tools:
    docker: {'status': 'missing', 'path': '', 'version': ''}
    git: {'status': 'missing', 'path': '', 'version': ''}
    node: {'status': 'missing', 'path': '', 'version': ''}
    npm: {'status': 'missing', 'path': '', 'version': ''}
    pip: {'status': 'missing', 'path': '', 'version': ''}
    python: {'status': 'missing', 'path': '', 'version': ''}
  missing: ['docker', 'git', 'node', 'npm', 'pip', 'python']