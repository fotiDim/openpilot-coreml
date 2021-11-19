# Openpilot CoreML

This is a conversion of Comma.ai's Openpilot main ML model, referred to as `supercombo`, to CoreML. 

# Why

Openpilot runs on Android and more recently on Linux. The hardware inteface called [Panda](https://comma.ai/shop/products/panda) is compatible with iOS (at least over WiFi). There have been 3rd party attempts to package OpenPilot as a standard Android App that can run on any Android phone. Since Apple's A-series chips seem to be [more powerful](https://www.notebookcheck.net/Google-s-Tensor-is-supposed-be-all-about-machine-learning-it-just-got-crushed-by-the-Apple-A15-Bionic-in-our-testing-with-the-new-Geekbench-ML-app.575439.0.html) for ML tasks than the current chips that are powering Android devices running OpenPilot on iOS could open up new posibilities.

# What's next

This is only the main model conversion. There is a lot of glue code that needs to be ran or ported to iOS.

For more information on OpenPilot you can visit the official [repo](https://github.com/commaai/openpilot).
