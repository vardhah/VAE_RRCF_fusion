# Latent Unit Mapping

Script to extract latent units into a csv file using the trained VAE model.

```
python3 latent-csv-generator.py    --use the trained B-VAE weights to generate CSV with latent unit parameters (mean, logvar, samples).
```

**Note**: These scripts will help you generate latent units using the trained B-VAE encoder. Pass an image dataset through the script and the trained VAE model. It will generate a csv with latent distributions.  
