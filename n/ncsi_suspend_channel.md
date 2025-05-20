# Function: <code>ncsi_suspend_channel</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff8188f9e0)
Location: net/ncsi/ncsi-manage.c:505
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff8188f9e0-ffffffff8188fb1f: ncsi_suspend_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff818c3e60)
Location: net/ncsi/ncsi-manage.c:527
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff818c3e60-ffffffff818c4066: ncsi_suspend_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff818ea7c0)
Location: net/ncsi/ncsi-manage.c:527
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff818ea7c0-ffffffff818ea9c5: ncsi_suspend_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81970310)
Location: net/ncsi/ncsi-manage.c:552
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff81970310-ffffffff8197051b: ncsi_suspend_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff819c9a30)
Location: net/ncsi/ncsi-manage.c:426
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff819c9a30-ffffffff819c9c42: ncsi_suspend_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a014b0)
Location: net/ncsi/ncsi-manage.c:464
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff81a014b0-ffffffff81a01755: ncsi_suspend_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:460
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff81a70610-ffffffff81a708b8: ncsi_suspend_channel (STB_LOCAL)
ffffffff81a71eda-ffffffff81a71ef0: ncsi_suspend_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:459
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff81aa6e40-ffffffff81aa70e8: ncsi_suspend_channel (STB_LOCAL)
ffffffff81aa869e-ffffffff81aa86b4: ncsi_suspend_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:461
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff81ba2d10-ffffffff81ba2fb8: ncsi_suspend_channel (STB_LOCAL)
ffffffff81ba45a4-ffffffff81ba45ba: ncsi_suspend_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:461
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff81bb2590-ffffffff81bb2838: ncsi_suspend_channel (STB_LOCAL)
ffffffff81c33a12-ffffffff81c33a28: ncsi_suspend_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:467
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff81ba15b0-ffffffff81ba1858: ncsi_suspend_channel (STB_LOCAL)
ffffffff81c25d26-ffffffff81c25d3c: ncsi_suspend_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:467
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff81c6efd0-ffffffff81c6f278: ncsi_suspend_channel (STB_LOCAL)
ffffffff81d428f7-ffffffff81d4290d: ncsi_suspend_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:467
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff81e12b60-ffffffff81e12e1e: ncsi_suspend_channel (STB_LOCAL)
ffffffff81f0f2b6-ffffffff81f0f2cb: ncsi_suspend_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81fe9690)
Location: net/ncsi/ncsi-manage.c:467
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff81fe9690-ffffffff81fe9959: ncsi_suspend_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff82065910)
Location: net/ncsi/ncsi-manage.c:467
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff82065910-ffffffff82065be3: ncsi_suspend_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff82138ab0)
Location: net/ncsi/ncsi-manage.c:467
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff82138ab0-ffffffff82138d83: ncsi_suspend_channel (STB_LOCAL)
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
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffff800010d79f70)
Location: net/ncsi/ncsi-manage.c:459
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffff800010d79f70-ffff800010d7a278: ncsi_suspend_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (c0e757d0)
Location: net/ncsi/ncsi-manage.c:459
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
c0e757d0-c0e75a7c: ncsi_suspend_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (c000000000eb9730)
Location: net/ncsi/ncsi-manage.c:459
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
c000000000eb9730-c000000000eb9ac8: ncsi_suspend_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffe0008a8b5c)
Location: net/ncsi/ncsi-manage.c:459
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffe0008a8b5c-ffffffe0008a8da4: ncsi_suspend_channel (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:459
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff81a461d0-ffffffff81a46478: ncsi_suspend_channel (STB_LOCAL)
ffffffff81a47a2e-ffffffff81a47a44: ncsi_suspend_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:459
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff81a02dc0-ffffffff81a03068: ncsi_suspend_channel (STB_LOCAL)
ffffffff81a0461e-ffffffff81a04634: ncsi_suspend_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:459
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff81ab2080-ffffffff81ab2328: ncsi_suspend_channel (STB_LOCAL)
ffffffff81ab38de-ffffffff81ab38f4: ncsi_suspend_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void ncsi_suspend_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:459
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff81abe430-ffffffff81abe6d8: ncsi_suspend_channel (STB_LOCAL)
ffffffff81abfc7e-ffffffff81abfc94: ncsi_suspend_channel.cold (STB_LOCAL)
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
