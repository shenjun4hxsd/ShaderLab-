
##子着色器（SubShader）

###&emsp;&emsp;语法：
```csharp
    SubShader { [Tags] [CommonState] Passdef [Passdef ...] }
```
<br>



**示例**
```csharp
    SubShader
    {
        Pass 
        {
            Lighting Off        // 关闭灯光
            SetTexture [_MainTex] { }
        }
    }
```



🔚



















