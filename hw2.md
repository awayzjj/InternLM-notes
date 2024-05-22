- **部署 `InternLM2-Chat-1.8B` 模型进行智能对话**

核心代码如下：

```python
AutoTokenizer.from_pretrained
AutoModelForCausalLM.from_pretrained
model.stream_chat
```

![截屏2024-05-23 07.26.34.png](images/hw2_1.png)

- **部署实战营优秀作品 `八戒-Chat-1.8B` 模型**

![截屏2024-05-23 07.11.23.png](images/hw2_2.png)

![截屏2024-05-23 07.08.50.png](images/hw2_3.png)

- **通过 `InternLM2-Chat-7B` 运行 `Lagent` 智能体 `Demo`**

核心代码如下：

```python
        model_inputs = model.prepare_inputs_for_generation(
            input_ids, **model_kwargs)
        # forward pass to get next token
        outputs = model(
            **model_inputs,
            return_dict=True,
            output_attentions=False,
            output_hidden_states=False,
        )
```

- **实践部署 `浦语·灵笔2` 模型**
