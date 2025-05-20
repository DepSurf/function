# Function: <code>unregister_sysrq_key</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int unregister_sysrq_key(int key, struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff814edd20)
Location: drivers/tty/sysrq.c:1073
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
```
**Symbols:**

```
ffffffff814edd20-ffffffff814edd35: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int unregister_sysrq_key(int key, struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff8153e9a0)
Location: drivers/tty/sysrq.c:1080
Inline: False
```
**Symbols:**

```
ffffffff8153e9a0-ffffffff8153e9b5: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int unregister_sysrq_key(int key, struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff8156aff0)
Location: drivers/tty/sysrq.c:1080
Inline: False
```
**Symbols:**

```
ffffffff8156aff0-ffffffff8156b005: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int unregister_sysrq_key(int key, struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff8157f620)
Location: drivers/tty/sysrq.c:1089
Inline: False
```
**Symbols:**

```
ffffffff8157f620-ffffffff8157f635: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int unregister_sysrq_key(int key, struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff815e4190)
Location: drivers/tty/sysrq.c:1094
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
```
**Symbols:**

```
ffffffff815e4190-ffffffff815e41a5: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int unregister_sysrq_key(int key, struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff8161d4f0)
Location: drivers/tty/sysrq.c:1094
Inline: False
```
**Symbols:**

```
ffffffff8161d4f0-ffffffff8161d505: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int unregister_sysrq_key(int key, struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff8163a750)
Location: drivers/tty/sysrq.c:1088
Inline: False
```
**Symbols:**

```
ffffffff8163a750-ffffffff8163a765: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int unregister_sysrq_key(int key, struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff8166eae0)
Location: drivers/tty/sysrq.c:1094
Inline: False
```
**Symbols:**

```
ffffffff8166eae0-ffffffff8166eaf5: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int unregister_sysrq_key(int key, struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff81691100)
Location: drivers/tty/sysrq.c:1087
Inline: False
```
**Symbols:**

```
ffffffff81691100-ffffffff81691115: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int unregister_sysrq_key(int key, const struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff817438c0)
Location: drivers/tty/sysrq.c:1096
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
```
**Symbols:**

```
ffffffff817438c0-ffffffff817438d5: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int unregister_sysrq_key(int key, const struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff8175f7d0)
Location: drivers/tty/sysrq.c:1139
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
```
**Symbols:**

```
ffffffff8175f7d0-ffffffff8175f7e5: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int unregister_sysrq_key(int key, const struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff81743630)
Location: drivers/tty/sysrq.c:1140
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
```
**Symbols:**

```
ffffffff81743630-ffffffff81743645: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int unregister_sysrq_key(int key, const struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff817c4120)
Location: drivers/tty/sysrq.c:1140
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
```
**Symbols:**

```
ffffffff817c4120-ffffffff817c4135: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int unregister_sysrq_key(int key, const struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff81900e10)
Location: drivers/tty/sysrq.c:1145
Inline: False
```
**Symbols:**

```
ffffffff81900e10-ffffffff81900e2f: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int unregister_sysrq_key(int key, const struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff81a5aae0)
Location: drivers/tty/sysrq.c:1145
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
```
**Symbols:**

```
ffffffff81a5aae0-ffffffff81a5aaff: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int unregister_sysrq_key(int key, const struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff81aa5110)
Location: drivers/tty/sysrq.c:1145
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
```
**Symbols:**

```
ffffffff81aa5110-ffffffff81aa512f: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int unregister_sysrq_key(u8 key, const struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff81af7b40)
Location: drivers/tty/sysrq.c:1144
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
```
**Symbols:**

```
ffffffff81af7b40-ffffffff81af7b63: unregister_sysrq_key (STB_GLOBAL)
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
int unregister_sysrq_key(int key, struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffff800010864460)
Location: drivers/tty/sysrq.c:1087
Inline: False
```
**Symbols:**

```
ffff800010864460-ffff800010864498: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int unregister_sysrq_key(int key, struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (c0969d8c)
Location: drivers/tty/sysrq.c:1087
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
```
**Symbols:**

```
c0969d8c-c0969db0: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int unregister_sysrq_key(int key, struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (c0000000009033e0)
Location: drivers/tty/sysrq.c:1087
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_unregister_io_module
```
**Symbols:**

```
c0000000009033e0-c0000000009033fc: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int unregister_sysrq_key(int key, struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffe00053ac7e)
Location: drivers/tty/sysrq.c:1087
Inline: False
```
**Symbols:**

```
ffffffe00053ac7e-ffffffe00053acb2: unregister_sysrq_key (STB_GLOBAL)
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
int unregister_sysrq_key(int key, struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff81656b80)
Location: drivers/tty/sysrq.c:1087
Inline: False
```
**Symbols:**

```
ffffffff81656b80-ffffffff81656b95: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int unregister_sysrq_key(int key, struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff81636f10)
Location: drivers/tty/sysrq.c:1087
Inline: False
```
**Symbols:**

```
ffffffff81636f10-ffffffff81636f25: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int unregister_sysrq_key(int key, struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff81684f40)
Location: drivers/tty/sysrq.c:1087
Inline: False
```
**Symbols:**

```
ffffffff81684f40-ffffffff81684f55: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int unregister_sysrq_key(int key, struct sysrq_key_op *op_p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/sysrq.c (ffffffff8169f470)
Location: drivers/tty/sysrq.c:1087
Inline: False
```
**Symbols:**

```
ffffffff8169f470-ffffffff8169f485: unregister_sysrq_key (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct sysrq_key_op *op_p</code> ➡️ <code>const struct sysrq_key_op *op_p</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int key</code> ➡️ <code>u8 key</code>
</li>
</ul>
</details>
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
