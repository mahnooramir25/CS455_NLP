Extending a Transformer-based sequence-to-sequence (seq2seq) model for machine translation, with a specific focus on low-resource language pairs.
| Feature                | Before | After | What It Means                             |
| ---------------------- | ------ | ----- | ----------------------------------------- |
| Urdu → English         | ✅      | ✅     | Translate from Urdu                       |
| English → Urdu         | ❌      | ✅     | Translate both ways now                   |
| BLEU Score             | ✅      | ✅     | Checks how close the result is to correct |
| METEOR Score           | ❌      | ✅     | Checks meaning similarity too             |
| Test with Own Sentence | ❌      | ✅     | You can try your own translations         |
| Save Results to CSV    | ❌      | ✅     | Keeps a record of translations and scores |
| Chart of Results       | ❌      | ✅     | Shows scores visually                     |
| Clean Modular Code     | ❌      | ✅     | Easy to extend and improve in the future  |

