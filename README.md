# multilingual_low_resource_dataset
A multilingual fake-news detection dataset covering Assamese, Bengali, Bhojpuri, and Odia, with source-derived labels independently verified by human reviewers, developed for HATNet research.

This repository contains a multilingual fake-news detection dataset comprising 56,343 articles across Assamese, Bengali, Bhojpuri, and Odia. It includes 33,650 articles labeled Real and 22,693 labeled Fake.

The dataset is provided as four language-specific CSV files. Each file contains two columns: `text`, containing the article text, and `label`, containing the source-derived Real or Fake label.

Labels were independently verified by eight human reviewers, with two reviewers assigned to each language. Both reviewers examined every article assigned to their language, using the article text and supporting evidence. Articles with reviewer disagreement were excluded.

This release contains article text and labels. It does not include publisher identifiers, event identifiers, or predefined training, validation, and test assignments.
