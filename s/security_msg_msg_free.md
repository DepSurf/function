# Function: <code>security_msg_msg_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133ea50)
Location: security/security.c:1037
Inline: False
Direct callers:
  - ipc/msgutil.c:free_msg
```
**Symbols:**

```
ffffffff8133ea50-ffffffff8133ea86: security_msg_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81374070)
Location: security/security.c:1061
Inline: False
Direct callers:
  - ipc/msgutil.c:free_msg
```
**Symbols:**

```
ffffffff81374070-ffffffff813740a6: security_msg_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138a9a0)
Location: security/security.c:1082
Inline: False
Direct callers:
  - ipc/msgutil.c:free_msg
```
**Symbols:**

```
ffffffff8138a9a0-ffffffff8138a9d6: security_msg_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a0000)
Location: security/security.c:1804
Inline: False
Direct callers:
  - ipc/msgutil.c:free_msg
```
**Symbols:**

```
ffffffff813a0000-ffffffff813a0049: security_msg_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c5bf0)
Location: security/security.c:1769
Inline: False
Direct callers:
  - ipc/msgutil.c:free_msg
  - security/security.c:security_msg_msg_alloc
```
**Symbols:**

```
ffffffff813c5bf0-ffffffff813c5c3f: security_msg_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5aa0)
Location: security/security.c:1186
Inline: False
Direct callers:
  - ipc/msgutil.c:free_msg
```
**Symbols:**

```
ffffffff813f5aa0-ffffffff813f5ad4: security_msg_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81411090)
Location: security/security.c:1801
Inline: False
Direct callers:
  - ipc/msgutil.c:free_msg
  - security/security.c:security_msg_msg_alloc
```
**Symbols:**

```
ffffffff81411090-ffffffff814110d7: security_msg_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143e8e0)
Location: security/security.c:1820
Inline: False
Direct callers:
  - ipc/msgutil.c:free_msg
  - security/security.c:security_msg_msg_alloc
```
**Symbols:**

```
ffffffff8143e8e0-ffffffff8143e929: security_msg_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814582d0)
Location: security/security.c:1859
Inline: False
Direct callers:
  - ipc/msgutil.c:free_msg
  - security/security.c:security_msg_msg_alloc
```
**Symbols:**

```
ffffffff814582d0-ffffffff81458317: security_msg_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ab1ef)
Location: security/security.c:2061
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
```
**Symbols:**

```
ffffffff814ab230-ffffffff814ab277: security_msg_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c87ef)
Location: security/security.c:2078
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
```
**Symbols:**

```
ffffffff814c8830-ffffffff814c8877: security_msg_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cee2f)
Location: security/security.c:2141
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
```
**Symbols:**

```
ffffffff814cee70-ffffffff814ceeb7: security_msg_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81527aef)
Location: security/security.c:2149
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
```
**Symbols:**

```
ffffffff81527b30-ffffffff81527b77: security_msg_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bca53)
Location: security/security.c:2160
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
```
**Symbols:**

```
ffffffff815bcad0-ffffffff815bcb1f: security_msg_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81668cd3)
Location: security/security.c:2236
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
```
**Symbols:**

```
ffffffff81668d60-ffffffff81668daf: security_msg_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a12d3)
Location: security/security.c:3703
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
```
**Symbols:**

```
ffffffff816a1360-ffffffff816a13af: security_msg_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816ddb53)
Location: security/security.c:3732
Inline: True
Inline callers:
  - security/security.c:security_msg_msg_alloc
Direct callers:
  - ipc/msgutil.c:load_msg
  - ipc/msgutil.c:alloc_msg
```
**Symbols:**

```
ffffffff816ddbe0-ffffffff816ddc2f: security_msg_msg_free (STB_GLOBAL)
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
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010544128)
Location: security/security.c:1859
Inline: False
Direct callers:
  - ipc/msgutil.c:free_msg
  - security/security.c:security_msg_msg_alloc
```
**Symbols:**

```
ffff800010544128-ffff80001054417c: security_msg_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fa03c)
Location: security/security.c:1859
Inline: False
Direct callers:
  - ipc/msgutil.c:free_msg
  - security/security.c:security_msg_msg_alloc
```
**Symbols:**

```
c06fa03c-c06fa094: security_msg_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c000000000698b80)
Location: security/security.c:1859
Inline: False
Direct callers:
  - ipc/msgutil.c:free_msg
  - security/security.c:security_msg_msg_alloc
```
**Symbols:**

```
c000000000698b80-c000000000698c0c: security_msg_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a037a)
Location: security/security.c:1859
Inline: False
Direct callers:
  - ipc/msgutil.c:free_msg
  - security/security.c:security_msg_msg_alloc
```
**Symbols:**

```
ffffffe0003a037a-ffffffe0003a03c2: security_msg_msg_free (STB_GLOBAL)
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
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814508b0)
Location: security/security.c:1859
Inline: False
Direct callers:
  - ipc/msgutil.c:free_msg
  - security/security.c:security_msg_msg_alloc
```
**Symbols:**

```
ffffffff814508b0-ffffffff814508f7: security_msg_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81441300)
Location: security/security.c:1859
Inline: False
Direct callers:
  - ipc/msgutil.c:free_msg
  - security/security.c:security_msg_msg_alloc
```
**Symbols:**

```
ffffffff81441300-ffffffff81441347: security_msg_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144c950)
Location: security/security.c:1859
Inline: False
Direct callers:
  - ipc/msgutil.c:free_msg
  - security/security.c:security_msg_msg_alloc
```
**Symbols:**

```
ffffffff8144c950-ffffffff8144c997: security_msg_msg_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void security_msg_msg_free(struct msg_msg *msg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81463d20)
Location: security/security.c:1859
Inline: False
Direct callers:
  - ipc/msgutil.c:free_msg
  - security/security.c:security_msg_msg_alloc
```
**Symbols:**

```
ffffffff81463d20-ffffffff81463d67: security_msg_msg_free (STB_GLOBAL)
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
