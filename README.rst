structlog-gelf
==============

This package adds a single module containing four classes:

* ``GELFFormatter`` allows formatting both ``structlog`` and regular
  ``logging`` messages as `GELF
  <https://docs.graylog.org/en/3.0/pages/gelf.html>`_.
* ``GraylogSocketHandler``; send a GELF-formatted message to Graylog
  using TCP.
* ``GraylogDatagramHandler``; send a GELF-formatted message to Graylog
  using UDP, with support for both both chunking and compression.
* ``GraylogAMQPHandler``; send a GELF-formatted message to Graylog
  using AMQP using `Pika <https://pypi.org/project/pika/>`_.

