Chef Databags in the cd-tools Repo
==================================

chef_pipelines Data Bag
-----------------------

cd-tools.json
~~~~~~~~~~~~~

.. code-block:: javascript

  {
    "id": "cd-tools",
    "gerrit_project": "cd-tools",
    "gerrit_host_name": "review.local",
    "chef_server_url": "https://api.opscode.com/organizations/opscode-cd",
    "node_name": "jenkins",
    "client_key": "/var/lib/jenkins/.chef/opscode-cd-jenkins.pem",
    "github_browser": "http://github.com/adamhjk/cd-tools/",
    "food_critic_options": "-f correctness -f ~FC017 -t any"
  }


