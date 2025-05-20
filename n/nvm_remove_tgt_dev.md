# Function: <code>nvm_remove_tgt_dev</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void nvm_remove_tgt_dev(struct nvm_tgt_dev *tgt_dev, int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815d8160)
Location: drivers/lightnvm/core.c:92
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
```
**Symbols:**

```
ffffffff815d8160-ffffffff815d8236: nvm_remove_tgt_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void nvm_remove_tgt_dev(struct nvm_tgt_dev *tgt_dev, int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff8163edb0)
Location: drivers/lightnvm/core.c:93
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
```
**Symbols:**

```
ffffffff8163edb0-ffffffff8163ee86: nvm_remove_tgt_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void nvm_remove_tgt_dev(struct nvm_tgt_dev *tgt_dev, int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff8167a160)
Location: drivers/lightnvm/core.c:111
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
```
**Symbols:**

```
ffffffff8167a160-ffffffff8167a232: nvm_remove_tgt_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void nvm_remove_tgt_dev(struct nvm_tgt_dev *tgt_dev, int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81698b90)
Location: drivers/lightnvm/core.c:111
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
```
**Symbols:**

```
ffffffff81698b90-ffffffff81698c62: nvm_remove_tgt_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void nvm_remove_tgt_dev(struct nvm_tgt_dev *tgt_dev, int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:99
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
ffffffff816d18f0-ffffffff816d19cd: nvm_remove_tgt_dev (STB_LOCAL)
ffffffff816d3b55-ffffffff816d3b76: nvm_remove_tgt_dev.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void nvm_remove_tgt_dev(struct nvm_tgt_dev *tgt_dev, int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816f5590)
Location: drivers/lightnvm/core.c:101
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
ffffffff816f5590-ffffffff816f5662: nvm_remove_tgt_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void nvm_remove_tgt_dev(struct nvm_tgt_dev *tgt_dev, int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817addf0)
Location: drivers/lightnvm/core.c:101
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
ffffffff817addf0-ffffffff817adec2: nvm_remove_tgt_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void nvm_remove_tgt_dev(struct nvm_tgt_dev *tgt_dev, int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817c2970)
Location: drivers/lightnvm/core.c:101
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
ffffffff817c2970-ffffffff817c2a42: nvm_remove_tgt_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void nvm_remove_tgt_dev(struct nvm_tgt_dev *tgt_dev, int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff817a5e30)
Location: drivers/lightnvm/core.c:101
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
ffffffff817a5e30-ffffffff817a5f02: nvm_remove_tgt_dev (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void nvm_remove_tgt_dev(struct nvm_tgt_dev *tgt_dev, int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffff8000108df690)
Location: drivers/lightnvm/core.c:101
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
ffff8000108df690-ffff8000108df7fc: nvm_remove_tgt_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void nvm_remove_tgt_dev(struct nvm_tgt_dev *tgt_dev, int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c09ce0cc)
Location: drivers/lightnvm/core.c:101
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
c09ce0cc-c09ce1dc: nvm_remove_tgt_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void nvm_remove_tgt_dev(struct nvm_tgt_dev *tgt_dev, int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c000000000972900)
Location: drivers/lightnvm/core.c:101
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
c000000000972900-c000000000972a9c: nvm_remove_tgt_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nvm_remove_tgt_dev(struct nvm_tgt_dev *tgt_dev, int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffe0005750a6)
Location: drivers/lightnvm/core.c:101
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
ffffffe0005750a6-ffffffe0005751b6: nvm_remove_tgt_dev (STB_LOCAL)
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
void nvm_remove_tgt_dev(struct nvm_tgt_dev *tgt_dev, int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816bad80)
Location: drivers/lightnvm/core.c:101
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
ffffffff816bad80-ffffffff816bae52: nvm_remove_tgt_dev (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void nvm_remove_tgt_dev(struct nvm_tgt_dev *tgt_dev, int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816e9250)
Location: drivers/lightnvm/core.c:101
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
ffffffff816e9250-ffffffff816e9322: nvm_remove_tgt_dev (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void nvm_remove_tgt_dev(struct nvm_tgt_dev *tgt_dev, int clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81703a90)
Location: drivers/lightnvm/core.c:101
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:__nvm_remove_target
  - drivers/lightnvm/core.c:nvm_create_tgt
```
**Symbols:**

```
ffffffff81703a90-ffffffff81703b62: nvm_remove_tgt_dev (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
