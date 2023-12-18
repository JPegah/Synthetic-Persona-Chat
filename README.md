# SPC: Synthetic-Persona-Chat Dataset
We introduce the Synthetic-Persona-Chat dataset, a persona-based conversational dataset, containing 5648 personas and 10906 conversations. It includes 8938, 1000, 968 conversations in 'train', 'validation' and 'test' splits.
Synthetic-Persona-Chat is created via the framework introduced in [Faithful Persona-based Conversational Dataset Generation with Large Language Models](https://arxiv.org/abs/2312.10007).

Each conversation in the dataset has the following format:

```
{
"User 1 Persona":[],
"User 2 Persona":[],
"Conversation":[]
}
```

## Citation
If you found SPC useful, please use the following citation.
```
@misc{jandaghi2023faithful,
      title={Faithful Persona-based Conversational Dataset Generation with Large Language Models}, 
      author={Pegah Jandaghi and XiangHai Sheng and Xinyi Bai and Jay Pujara and Hakim Sidahmed},
      year={2023},
      eprint={2312.10007},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```

## License
[CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## Contact
* Pegah Jandaghi (jandaghi@usc.edu)
* Xianghai Sheng (xhs@google.com)
* Xinyi Bai (shinii@google.com)
* Jay Pujara (jpujara@isi.edu)
* Hakim Sidahmed (hsidahmed@google.com)