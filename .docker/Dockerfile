FROM mam10eks/splade_tira:0.0.1

COPY run_retrieval.py /workspace/

ENTRYPOINT [ "python3", "/workspace/run_retrieval.py", "--input", "$inputDataset", "--output", "$outputDir" ]
