# Email-Spam-Detection
Classification and Semi-supervised Anomaly Detection on Ham-Spam Email Dataset

EmailSpam -> Classification<br>
EmailSpam_AD -> Semi-supervised AD<br><br>

Classification uses a LSTM net to classify ham-spam emails.<br><br>
The anomaly detection approach uses an AUTOENCODER to rebuild the test samples and to assign an outlierness score to the samples. The autoencoder was trained only on normal data.
