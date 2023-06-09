
Kolibri Google Analytics plugin
===============================


How can I install this plugin?
------------------------------

1. Inside your Kolibri virtual environment:
    ``pip install kolibri_google_analytics_plugin``

2. Activate the plugin:

    ``kolibri plugin kolibri_google_analytics_plugin enable``

3. Restart Kolibri.

How can I install this plugin for development?
------------------------------

1. Download this repo.

2. Open a terminal in your Kolibri repo.

3. Run the following commands:

    ``pip install -e <LOCAL-PATH-TO-REPO>``

    ``kolibri plugin kolibri_google_analytics_plugin enable``

4. Then run the commands to install frontend packages in Kolibri, this plugin will have its dependencies recursively installed.


How to publish to PyPi?
------------------------------

1. Follow the instructions above to install the plugin for development.

2. From the Kolibri directory run the frontend build command.

3. Update `setup.py` to a newer version.

4. In the terminal move to the root level of repo dir and run the following command to publish to PyPi:

    ``make release``