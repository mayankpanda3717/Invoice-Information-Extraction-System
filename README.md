# Invoice-Information-Extraction-System
Invoice information extraction is the process of pulling critical data like invoice number, amount, and date from the invoice. Accounts Payable (AP) teams must enter all invoice information into your organization’s accounting software for processing. The Invoice Information Extraction System extracts useful information from a scanned copy of an invoice.

The steps involved are:
* Downloading the annotated dataset of invoices from hugging face.
* Using the downloaded dataset to finetune the Lilt Model.
* Using the finetuned model for inference.


**Note:** We could further improve this system by preprocessing the invoice images which we are giving to our model as an input. This work could be achieved using the OpenCV library.


### The predicted outputs obtained on giving a new invoice image would look something like:
![image](https://github.com/mayankpanda3717/Invoice-Information-Extraction-System/assets/148647754/bb5d5ad3-a33b-458a-be55-1545cc780614)


**If your laptop's specifications are not quite good then you can use Google Colab to run this piece of code. Make sure that you activate the GPU on colab that's available free of cost.** 





