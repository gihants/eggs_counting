# eggs_counting


# creating tfrecords

# for training data:
python generate_tfrecord.py --csv_input=data/train_labels.csv  --output_path=data/train.record

# for testing data:
python generate_tfrecord.py --csv_input=data/test_labels.csv  --output_path=data/test.record

