<p align="center">
<img alt="Logo" width=18% src="static/logo/redata_logo_cicle.svg"/>
</p>
<p align="center">
<a href="https://join.slack.com/t/re-data/shared_invite/zt-vkauq1y8-tL4R4_H5nZoVvyXyy0hdug"><img alt="Slack" src="https://img.shields.io/badge/chat-slack-blue.svg"/></a>
<img alt="License" src="https://img.shields.io/github/license/redata-team/redata?color=violet"/>
<img alt="Last commit" src="https://img.shields.io/github/last-commit/redata-team/redata"/>
</p>

# What is re_data?

re_data is a set of tools (dbt macros & models) that helps you make sure your data pipelines are clean & reliable. 😊

## Data Preparation

re_data data preparation macros help you clean your data faster, with less code & a smaller chance of errors.
Currently, we support four types of data preparation:

- data cleaning
- data filtering
- data normalization
- data validation

## Data Monitoring

re_data metrics & alerts models contain information about data quality which lets you discover bad data much faster. You can:
 - use built-in metrics & extend them with your code
 - test them as regular dbt models
 - visualize them in your favourite BI tool
 - trigger external (Slack/Pagerduty/etc.) alerts based on them


# Getting started

[Check our docs!](https://re-data.github.io/re-data/latest/docs/introduction/whatis) 📓 📓

[Join re_data community on Slack](https://join.slack.com/t/re-data/shared_invite/zt-vkauq1y8-tL4R4_H5nZoVvyXyy0hdug) (we are very responsive there)

# Source code

As dbt packages currently need to be a seperate github repos, most of source code of re_data can be found [here](https://github.com/re-data/dbt-re-data)

# Integrations

We support most of the main data warehouses supported by dbt. We plan to add support for Spark (now officially supported by dbt).

|      | Integration | Status     |
| :---        |    :----:   |          ---: |
| <img height="40" src="https://miro.medium.com/max/1024/0*eDEy4S8zFfYnRt1X.png" />      | BigQuery       | Supported |
| <img height="40" src="https://www.pngkey.com/png/full/20-201458_when-ubers-engineering-team-published-a-blog-post.png" />   | PostgreSQL        | Supported      |
| <img height="40" src="https://dbdb.io/media/logos/amazon-redshift.png" />  | Redshift        | Supported      |
| <img height="40" src="https://www.snowflake.com/wp-content/themes/snowflake/img/snowflake-logo-blue@2x.png" />  | Snowflake        | Supported      |
| <img height="40" src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/f3/Apache_Spark_logo.svg/1200px-Apache_Spark_logo.svg.png" />  | Apache Spark        | Planned      |


# License
re_data is licensed under the MIT license. See the [LICENSE](LICENSE) file for licensing information.

# Contributing

We love all contributions :heart_eyes: bigger and smaller.

Check out the current list of issues [here](https://github.com/re-data/re-data/issues) and see if you like anything from there. Also, feel welcome to join our [Slack](https://join.slack.com/t/re-data/shared_invite/zt-vkauq1y8-tL4R4_H5nZoVvyXyy0hdug) and suggest ideas or set up a live session [here](https://calendly.com/mateuszklimek/30min). 

And if you got this far and like what we are building, support us! Star https://github.com/re-data/re-data on Github :star_struck:


