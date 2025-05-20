# Function: <code>fw_set_page_data</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff8155e780)
Location: drivers/base/firmware_class.c:387
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
Direct callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff8155e780-ffffffff8155e7be: fw_set_page_data.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void fw_set_page_data(struct firmware_buf *buf, struct firmware *fw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815b2d20)
Location: drivers/base/firmware_class.c:383
Inline: True
Direct callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff815b2d20-ffffffff815b2d7f: fw_set_page_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void fw_set_page_data(struct firmware_buf *buf, struct firmware *fw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815e2130)
Location: drivers/base/firmware_class.c:451
Inline: True
Direct callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:_request_firmware
```
**Symbols:**

```
ffffffff815e2130-ffffffff815e218f: fw_set_page_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff815f7c2d)
Location: drivers/base/firmware_class.c:447
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:assign_firmware_buf
Direct callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:assign_firmware_buf
```
**Symbols:**

```
ffffffff815f6eb0-ffffffff815f6ee9: fw_set_page_data.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/firmware_class.c (ffffffff8165fbcd)
Location: drivers/base/firmware_class.c:451
Inline: True
Inline callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:assign_firmware_buf
Direct callers:
  - drivers/base/firmware_class.c:_request_firmware
  - drivers/base/firmware_class.c:assign_firmware_buf
```
**Symbols:**

```
ffffffff8165ede0-ffffffff8165ee19: fw_set_page_data.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fw_set_page_data(struct fw_priv *fw_priv, struct firmware *fw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81699bd0)
Location: drivers/base/firmware_loader/main.c:355
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff81699bd0-ffffffff81699c27: fw_set_page_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fw_set_page_data(struct fw_priv *fw_priv, struct firmware *fw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816ba420)
Location: drivers/base/firmware_loader/main.c:361
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff816ba420-ffffffff816ba477: fw_set_page_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void fw_set_page_data(struct fw_priv *fw_priv, struct firmware *fw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816f4700)
Location: drivers/base/firmware_loader/main.c:545
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff816f4700-ffffffff816f4756: fw_set_page_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void fw_set_page_data(struct fw_priv *fw_priv, struct firmware *fw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81718b00)
Location: drivers/base/firmware_loader/main.c:545
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff81718b00-ffffffff81718b56: fw_set_page_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fw_set_page_data(struct fw_priv *fw_priv, struct firmware *fw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817d4730)
Location: drivers/base/firmware_loader/main.c:553
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff817d4730-ffffffff817d477e: fw_set_page_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fw_set_page_data(struct fw_priv *fw_priv, struct firmware *fw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817e90f0)
Location: drivers/base/firmware_loader/main.c:588
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff817e90f0-ffffffff817e913e: fw_set_page_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fw_set_page_data(struct fw_priv *fw_priv, struct firmware *fw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff817cd8c0)
Location: drivers/base/firmware_loader/main.c:590
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff817cd8c0-ffffffff817cd90e: fw_set_page_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fw_set_page_data(struct fw_priv *fw_priv, struct firmware *fw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff818580b0)
Location: drivers/base/firmware_loader/main.c:591
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff818580b0-ffffffff818580fb: fw_set_page_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fw_set_page_data(struct fw_priv *fw_priv, struct firmware *fw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8199e790)
Location: drivers/base/firmware_loader/main.c:594
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff8199e790-ffffffff8199e803: fw_set_page_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fw_set_page_data(struct fw_priv *fw_priv, struct firmware *fw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b10130)
Location: drivers/base/firmware_loader/main.c:594
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff81b10130-ffffffff81b101a3: fw_set_page_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fw_set_page_data(struct fw_priv *fw_priv, struct firmware *fw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81b5e1f0)
Location: drivers/base/firmware_loader/main.c:603
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff81b5e1f0-ffffffff81b5e263: fw_set_page_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fw_set_page_data(struct fw_priv *fw_priv, struct firmware *fw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81bb1b00)
Location: drivers/base/firmware_loader/main.c:604
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff81bb1b00-ffffffff81bb1b73: fw_set_page_data (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void fw_set_page_data(struct fw_priv *fw_priv, struct firmware *fw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffff80001090bdf8)
Location: drivers/base/firmware_loader/main.c:545
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffff80001090bdf8-ffff80001090be74: fw_set_page_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void fw_set_page_data(struct fw_priv *fw_priv, struct firmware *fw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c09f5104)
Location: drivers/base/firmware_loader/main.c:545
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
c09f5104-c09f5188: fw_set_page_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void fw_set_page_data(struct fw_priv *fw_priv, struct firmware *fw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (c0000000009ab460)
Location: drivers/base/firmware_loader/main.c:545
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
c0000000009ab460-c0000000009ab4e8: fw_set_page_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void fw_set_page_data(struct fw_priv *fw_priv, struct firmware *fw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffe00059152c)
Location: drivers/base/firmware_loader/main.c:545
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffe00059152c-ffffffe0005915a6: fw_set_page_data (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void fw_set_page_data(struct fw_priv *fw_priv, struct firmware *fw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816dee30)
Location: drivers/base/firmware_loader/main.c:545
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff816dee30-ffffffff816dee86: fw_set_page_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void fw_set_page_data(struct fw_priv *fw_priv, struct firmware *fw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff816b9470)
Location: drivers/base/firmware_loader/main.c:545
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff816b9470-ffffffff816b94c6: fw_set_page_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void fw_set_page_data(struct fw_priv *fw_priv, struct firmware *fw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff8170c7c0)
Location: drivers/base/firmware_loader/main.c:545
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff8170c7c0-ffffffff8170c816: fw_set_page_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void fw_set_page_data(struct fw_priv *fw_priv, struct firmware *fw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/firmware_loader/main.c (ffffffff81727170)
Location: drivers/base/firmware_loader/main.c:545
Inline: False
Direct callers:
  - drivers/base/firmware_loader/main.c:_request_firmware
  - drivers/base/firmware_loader/main.c:assign_fw
```
**Symbols:**

```
ffffffff81727170-ffffffff817271c6: fw_set_page_data (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
