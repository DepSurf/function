# Function: <code>__deflate_exit</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __deflate_exit(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff8146f080)
Location: crypto/deflate.c:161
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
```
**Symbols:**

```
ffffffff8146f080-ffffffff8146f0b3: __deflate_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __deflate_exit(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff8148ca30)
Location: crypto/deflate.c:161
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
```
**Symbols:**

```
ffffffff8148ca30-ffffffff8148ca63: __deflate_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __deflate_exit(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814ba110)
Location: crypto/deflate.c:157
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
```
**Symbols:**

```
ffffffff814ba110-ffffffff814ba143: __deflate_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __deflate_exit(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814d2ee0)
Location: crypto/deflate.c:157
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
```
**Symbols:**

```
ffffffff814d2ee0-ffffffff814d2f13: __deflate_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff815320c5)
Location: crypto/deflate.c:157
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff8154f015)
Location: crypto/deflate.c:157
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff81557885)
Location: crypto/deflate.c:157
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff815b8b35)
Location: crypto/deflate.c:157
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff81661f65)
Location: crypto/deflate.c:157
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff8171bea5)
Location: crypto/deflate.c:157
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff81757635)
Location: crypto/deflate.c:157
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff81799535)
Location: crypto/deflate.c:140
Inline: True
Inline callers:
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
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
void __deflate_exit(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffff8000105cf450)
Location: crypto/deflate.c:157
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
```
**Symbols:**

```
ffff8000105cf450-ffff8000105cf494: __deflate_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __deflate_exit(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (c077d214)
Location: crypto/deflate.c:157
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
```
**Symbols:**

```
c077d214-c077d24c: __deflate_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __deflate_exit(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (c00000000075b380)
Location: crypto/deflate.c:157
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
```
**Symbols:**

```
c00000000075b380-c00000000075b3e4: __deflate_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __deflate_exit(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffe0004143ac)
Location: crypto/deflate.c:157
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
```
**Symbols:**

```
ffffffe0004143ac-ffffffe0004143f6: __deflate_exit (STB_LOCAL)
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
void __deflate_exit(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814cb4c0)
Location: crypto/deflate.c:157
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
```
**Symbols:**

```
ffffffff814cb4c0-ffffffff814cb4f3: __deflate_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __deflate_exit(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814bbee0)
Location: crypto/deflate.c:157
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
```
**Symbols:**

```
ffffffff814bbee0-ffffffff814bbf13: __deflate_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __deflate_exit(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814c7550)
Location: crypto/deflate.c:157
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
```
**Symbols:**

```
ffffffff814c7550-ffffffff814c7583: __deflate_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __deflate_exit(void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In crypto/deflate.c (ffffffff814e0020)
Location: crypto/deflate.c:157
Inline: False
Direct callers:
  - crypto/deflate.c:deflate_exit
  - crypto/deflate.c:deflate_free_ctx
```
**Symbols:**

```
ffffffff814e0020-ffffffff814e0053: __deflate_exit (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
