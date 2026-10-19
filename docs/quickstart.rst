Quickstart
==========

Load the bundled sample measurements, calculate summaries for each column, and write them to a text report:

.. code-block:: python

   import ci_course

   measurements = ci_course.load_measurements()
   summaries = ci_course.summarise_all(measurements)
   report_path = ci_course.write_report(summaries, "summary.txt")

   print(f"Report written to {report_path}")
