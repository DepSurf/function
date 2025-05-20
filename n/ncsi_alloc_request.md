# Function: <code>ncsi_alloc_request</code>

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
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, bool driven);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff8188f120)
Location: net/ncsi/ncsi-manage.c:408
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff8188f120-ffffffff8188f261: ncsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff818c3520)
Location: net/ncsi/ncsi-manage.c:428
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff818c3520-ffffffff818c3670: ncsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff818e9eb0)
Location: net/ncsi/ncsi-manage.c:428
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff818e9eb0-ffffffff818e9fe5: ncsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff8196f5f0)
Location: net/ncsi/ncsi-manage.c:453
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff8196f5f0-ffffffff8196f715: ncsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff819c8d00)
Location: net/ncsi/ncsi-manage.c:327
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff819c8d00-ffffffff819c8e2c: ncsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a00c40)
Location: net/ncsi/ncsi-manage.c:350
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81a00c40-ffffffff81a00d82: ncsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a6fe60)
Location: net/ncsi/ncsi-manage.c:346
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81a6fe60-ffffffff81a6ff5d: ncsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81aa6690)
Location: net/ncsi/ncsi-manage.c:345
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81aa6690-ffffffff81aa678d: ncsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81ba2530)
Location: net/ncsi/ncsi-manage.c:347
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_alloc_command
```
**Symbols:**

```
ffffffff81ba2530-ffffffff81ba2606: ncsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81bb1db0)
Location: net/ncsi/ncsi-manage.c:347
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_alloc_command
```
**Symbols:**

```
ffffffff81bb1db0-ffffffff81bb1e86: ncsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81ba0dd0)
Location: net/ncsi/ncsi-manage.c:353
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81ba0dd0-ffffffff81ba0ea6: ncsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:353
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81d426de-ffffffff81d42724: ncsi_alloc_request.cold (STB_LOCAL)
ffffffff81c6e6d0-ffffffff81c6e892: ncsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:353
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81f0f083-ffffffff81f0f0c9: ncsi_alloc_request.cold (STB_LOCAL)
ffffffff81e12240-ffffffff81e12412: ncsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:353
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff820b59cd-ffffffff820b5a13: ncsi_alloc_request.cold (STB_LOCAL)
ffffffff81fe8c90-ffffffff81fe8e62: ncsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:353
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff82136f50-ffffffff82136f96: ncsi_alloc_request.cold (STB_LOCAL)
ffffffff82064f10-ffffffff820650e2: ncsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:353
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff82218db2-ffffffff82218df8: ncsi_alloc_request.cold (STB_LOCAL)
ffffffff821380b0-ffffffff82138282: ncsi_alloc_request (STB_GLOBAL)
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
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffff800010d79410)
Location: net/ncsi/ncsi-manage.c:345
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffff800010d79410-ffff800010d79580: ncsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (c0e74f44)
Location: net/ncsi/ncsi-manage.c:345
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
c0e74f44-c0e75044: ncsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (c000000000eb8c20)
Location: net/ncsi/ncsi-manage.c:345
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
c000000000eb8c20-c000000000eb8db4: ncsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffe0008a841a)
Location: net/ncsi/ncsi-manage.c:345
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffe0008a841a-ffffffe0008a8522: ncsi_alloc_request (STB_GLOBAL)
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
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a45a20)
Location: net/ncsi/ncsi-manage.c:345
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81a45a20-ffffffff81a45b1d: ncsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a02610)
Location: net/ncsi/ncsi-manage.c:345
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81a02610-ffffffff81a0270d: ncsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81ab18d0)
Location: net/ncsi/ncsi-manage.c:345
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81ab18d0-ffffffff81ab19cd: ncsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct ncsi_request *ncsi_alloc_request(struct ncsi_dev_priv *ndp, unsigned int req_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81abdc80)
Location: net/ncsi/ncsi-manage.c:345
Inline: False
Direct callers:
  - net/ncsi/ncsi-cmd.c:ncsi_xmit_cmd
```
**Symbols:**

```
ffffffff81abdc80-ffffffff81abdd7d: ncsi_alloc_request (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int req_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>bool driven</code>
</li>
</ul>
</details>
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
