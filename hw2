- **部署 `InternLM2-Chat-1.8B` 模型进行智能对话**

核心代码如下：

```python
AutoTokenizer.from_pretrained
AutoModelForCausalLM.from_pretrained
model.stream_chat
```

![截屏2024-05-23 07.26.34.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e309157e-3438-423c-99d1-596e42668161/62124b81-b33a-4da0-b537-b2e60f430f4f/%E6%88%AA%E5%B1%8F2024-05-23_07.26.34.png)

- **部署实战营优秀作品 `八戒-Chat-1.8B` 模型**

![截屏2024-05-23 07.11.23.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e309157e-3438-423c-99d1-596e42668161/9298f8a7-41bf-4e21-aaf9-70f28571dac8/%E6%88%AA%E5%B1%8F2024-05-23_07.11.23.png)

![截屏2024-05-23 07.08.50.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e309157e-3438-423c-99d1-596e42668161/1d94fd0e-3b8a-4308-b4e9-2557b48dfa56/%E6%88%AA%E5%B1%8F2024-05-23_07.08.50.png)

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
