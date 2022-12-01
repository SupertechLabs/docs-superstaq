.. docs-superstaq documentation master file, created by
   sphinx-quickstart on Thu Sep  8 16:32:42 2022.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

SuperstaQ Documentation
=======================
Welcome to SuperstaQ's documentation! Here you can find more information about our packages ``cirq-superstaq`` and ``qiskit-superstaq``, which allow access to SuperstaQ via a Web API through `Cirq <https://github.com/quantumlib/Cirq>`_ and `Qiskit <https://qiskit.org/>`_, respectively.

Check out some of our demos to see how SuperstaQ can help you:

.. raw:: html

   <div class="index-demos">
      <div class="index-demos-box">
         <div class="index-demos-headers"><a href="demos/community_detection_football.html">Community Detection</a></div>
         <div class="index-demos-desc">A general form of a network problem that can be used to detect fraud rings in transaction networks.</div>
      </div>
      <div class="index-demos-box">
         <div class="index-demos-headers"><a href="demos/currency_arbitrage.html">Currency Arbitrage</a></div>
         <div class="index-demos-desc">See how quantum techniques can find the most profitable arbitrage opportunity in a network of exchange rates where rates aren’t necessarily symmetrical.</div>
      </div>
      <div class="index-demos-box">
         <div class="index-demos-headers"><a href="demos/goal_based_investing.html">Goal Based Investing</a></div>
         <div class="index-demos-desc">An example of how to allocate wealth and investments to maximize expected value delivered over a specific time horizon.</div>
      </div>
   </div>
   <br>


Learn more about SuperstaQ `here <https://www.super.tech/about-superstaq/>`_.


.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: Get Started

   installation
   example_code

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: Demos

   demos/community_detection_football
   demos/currency_arbitrage
   demos/goal_based_investing
   demos/insurance_pricing
   demos/risk_neutral_probabilities_options
   demos/transaction_settlement

.. toctree::
   :maxdepth: 1
   :hidden:
   :caption: Clients

   cirq_superstaq
   qiskit_superstaq