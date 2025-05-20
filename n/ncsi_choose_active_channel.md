# Function: <code>ncsi_choose_active_channel</code>

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
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff8188fb20)
Location: net/ncsi/ncsi-manage.c:697
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_start_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff8188fb20-ffffffff8188fc23: ncsi_choose_active_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff818c4070)
Location: net/ncsi/ncsi-manage.c:782
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff818c4070-ffffffff818c4201: ncsi_choose_active_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff818ea9d0)
Location: net/ncsi/ncsi-manage.c:782
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff818ea9d0-ffffffff818eab52: ncsi_choose_active_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81970520)
Location: net/ncsi/ncsi-manage.c:966
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff81970520-ffffffff819706f4: ncsi_choose_active_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff819c9c50)
Location: net/ncsi/ncsi-manage.c:843
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff819c9c50-ffffffff819c9e90: ncsi_choose_active_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a02300)
Location: net/ncsi/ncsi-manage.c:1150
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff81a02300-ffffffff81a02614: ncsi_choose_active_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:1146
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff81a71330-ffffffff81a715e6: ncsi_choose_active_channel (STB_LOCAL)
ffffffff81a720a6-ffffffff81a72110: ncsi_choose_active_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:1143
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff81aa7b20-ffffffff81aa7dd6: ncsi_choose_active_channel (STB_LOCAL)
ffffffff81aa886a-ffffffff81aa88d4: ncsi_choose_active_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:1170
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
```
**Symbols:**

```
ffffffff81ba38f0-ffffffff81ba3ba6: ncsi_choose_active_channel (STB_LOCAL)
ffffffff81ba4749-ffffffff81ba47b3: ncsi_choose_active_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:1170
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
```
**Symbols:**

```
ffffffff81bb3170-ffffffff81bb341d: ncsi_choose_active_channel (STB_LOCAL)
ffffffff81c33bb4-ffffffff81c33c15: ncsi_choose_active_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:1176
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
```
**Symbols:**

```
ffffffff81ba2170-ffffffff81ba2426: ncsi_choose_active_channel (STB_LOCAL)
ffffffff81c25f1f-ffffffff81c25f89: ncsi_choose_active_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:1228
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
```
**Symbols:**

```
ffffffff81c6fc30-ffffffff81c6ff2b: ncsi_choose_active_channel (STB_LOCAL)
ffffffff81d42b36-ffffffff81d42c3b: ncsi_choose_active_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:1228
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
```
**Symbols:**

```
ffffffff81e137e0-ffffffff81e13ae5: ncsi_choose_active_channel (STB_LOCAL)
ffffffff81f0f4a6-ffffffff81f0f5cb: ncsi_choose_active_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:1228
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
```
**Symbols:**

```
ffffffff81fea4d0-ffffffff81fea84c: ncsi_choose_active_channel (STB_LOCAL)
ffffffff820b5b5d-ffffffff820b5c01: ncsi_choose_active_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:1228
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
```
**Symbols:**

```
ffffffff82066790-ffffffff82066b09: ncsi_choose_active_channel (STB_LOCAL)
ffffffff821370cc-ffffffff82137162: ncsi_choose_active_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:1223
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_probe_channel
```
**Symbols:**

```
ffffffff82139950-ffffffff82139cc9: ncsi_choose_active_channel (STB_LOCAL)
ffffffff82218f2e-ffffffff82218fc4: ncsi_choose_active_channel.cold (STB_LOCAL)
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
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffff800010d7b220)
Location: net/ncsi/ncsi-manage.c:1143
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffff800010d7b220-ffff800010d7b638: ncsi_choose_active_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (c0e76628)
Location: net/ncsi/ncsi-manage.c:1143
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
c0e76628-c0e7695c: ncsi_choose_active_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (c000000000eba970)
Location: net/ncsi/ncsi-manage.c:1143
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
c000000000eba970-c000000000ebad94: ncsi_choose_active_channel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffe0008a97c4)
Location: net/ncsi/ncsi-manage.c:1143
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffe0008a97c4-ffffffe0008a9a72: ncsi_choose_active_channel (STB_LOCAL)
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
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:1143
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff81a46eb0-ffffffff81a47166: ncsi_choose_active_channel (STB_LOCAL)
ffffffff81a47bfa-ffffffff81a47c64: ncsi_choose_active_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:1143
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff81a03aa0-ffffffff81a03d56: ncsi_choose_active_channel (STB_LOCAL)
ffffffff81a047ea-ffffffff81a04854: ncsi_choose_active_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:1143
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff81ab2d60-ffffffff81ab3016: ncsi_choose_active_channel (STB_LOCAL)
ffffffff81ab3aaa-ffffffff81ab3b14: ncsi_choose_active_channel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ncsi_choose_active_channel(struct ncsi_dev_priv *ndp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:1143
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_reset_dev
  - net/ncsi/ncsi-manage.c:ncsi_process_next_channel
  - net/ncsi/ncsi-manage.c:ncsi_dev_work
```
**Symbols:**

```
ffffffff81abf100-ffffffff81abf3b6: ncsi_choose_active_channel (STB_LOCAL)
ffffffff81abfe46-ffffffff81abfeb0: ncsi_choose_active_channel.cold (STB_LOCAL)
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
