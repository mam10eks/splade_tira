# splade_tira

Run it locally via (still in progress):

```
python3 run_retrieval.py --input workshop-on-open-web-search/document-processing-20231027-training --output out
```

Command to build the dev container:

```
docker build -t mam10eks/splade_tira:0.0.1 -f .docker/Dockerfile.dev .
```

```
docker build -t registry.webis.de/code-research/tira/tira-user-tira-user-naverlabseurope/my-software:0.0.1 -f .docker/Dockerfile .
```

```
tira-run \
    --image registry.webis.de/code-research/tira/tira-user-tira-user-naverlabseurope/my-software:0.0.1 \
    --input-directory sample-input-full-rank
```

tira-run --image registry.webis.de/code-research/tira/tira-user-pan23-cdav-baseline/galicia22a:0.0.2 --input-directory pan23-authorship-verification-train-20230322-training/ --output-directory o --command 'python3 /app/model/codes/predict.py -i $inputDataset -o $outputDir'


Upload the image via:

```
docker push registry.webis.de/code-research/tira/tira-user-tira-user-naverlabseurope/my-software:0.0.1
```

TODO: Maik adjust the tira-run command so that it can use podman as Docker runtime.

### Colab link

https://colab.research.google.com/drive/1PNzl3efkI90BpCiQGfRjd7HMrUo3frxB?usp=sharing
