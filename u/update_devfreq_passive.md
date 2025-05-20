# Function: <code>update_devfreq_passive</code>

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
int update_devfreq_passive(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/governor_passive.c (ffffffff81753150)
Location: drivers/devfreq/governor_passive.c:98
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
```
**Symbols:**

```
ffffffff81753150-ffffffff817531cf: update_devfreq_passive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int update_devfreq_passive(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/governor_passive.c (ffffffff8177ef40)
Location: drivers/devfreq/governor_passive.c:98
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
```
**Symbols:**

```
ffffffff8177ef40-ffffffff8177eff3: update_devfreq_passive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int update_devfreq_passive(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/governor_passive.c (ffffffff8179da00)
Location: drivers/devfreq/governor_passive.c:98
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
```
**Symbols:**

```
ffffffff8179da00-ffffffff8179dab3: update_devfreq_passive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int update_devfreq_passive(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/governor_passive.c (ffffffff81814b50)
Location: drivers/devfreq/governor_passive.c:98
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
```
**Symbols:**

```
ffffffff81814b50-ffffffff81814c0f: update_devfreq_passive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int update_devfreq_passive(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/governor_passive.c (ffffffff8185ea40)
Location: drivers/devfreq/governor_passive.c:98
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
```
**Symbols:**

```
ffffffff8185ea40-ffffffff8185eaff: update_devfreq_passive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int update_devfreq_passive(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/governor_passive.c (ffffffff8187e3e0)
Location: drivers/devfreq/governor_passive.c:98
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
```
**Symbols:**

```
ffffffff8187e3e0-ffffffff8187e49f: update_devfreq_passive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int update_devfreq_passive(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/governor_passive.c (0)
Location: drivers/devfreq/governor_passive.c:95
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
```
**Symbols:**

```
ffffffff818c8a40-ffffffff818c8af1: update_devfreq_passive (STB_LOCAL)
ffffffff818c8c1e-ffffffff818c8c37: update_devfreq_passive.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int update_devfreq_passive(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/governor_passive.c (0)
Location: drivers/devfreq/governor_passive.c:95
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
```
**Symbols:**

```
ffffffff818fae20-ffffffff818faed1: update_devfreq_passive (STB_LOCAL)
ffffffff818fb06b-ffffffff818fb084: update_devfreq_passive.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/devfreq/governor_passive.c (0)
Location: drivers/devfreq/governor_passive.c:95
Inline: True
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
```
**Symbols:**

```
ffffffff819d1a80-ffffffff819d1b24: update_devfreq_passive.isra.0 (STB_LOCAL)
ffffffff819d1b75-ffffffff819d1b8e: update_devfreq_passive.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
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
int update_devfreq_passive(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/governor_passive.c (ffff800010b878b0)
Location: drivers/devfreq/governor_passive.c:95
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
```
**Symbols:**

```
ffff800010b878b0-ffff800010b87970: update_devfreq_passive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int update_devfreq_passive(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/governor_passive.c (c0c6a774)
Location: drivers/devfreq/governor_passive.c:95
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
```
**Symbols:**

```
c0c6a774-c0c6a844: update_devfreq_passive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int update_devfreq_passive(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/governor_passive.c (c000000000c66a60)
Location: drivers/devfreq/governor_passive.c:95
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
```
**Symbols:**

```
c000000000c66a60-c000000000c66b74: update_devfreq_passive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int update_devfreq_passive(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/devfreq/governor_passive.c (ffffffe0007306da)
Location: drivers/devfreq/governor_passive.c:95
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
```
**Symbols:**

```
ffffffe0007306da-ffffffe000730786: update_devfreq_passive (STB_LOCAL)
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
int update_devfreq_passive(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/governor_passive.c (0)
Location: drivers/devfreq/governor_passive.c:95
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
```
**Symbols:**

```
ffffffff8189c150-ffffffff8189c201: update_devfreq_passive (STB_LOCAL)
ffffffff8189c39b-ffffffff8189c3b4: update_devfreq_passive.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int update_devfreq_passive(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/governor_passive.c (0)
Location: drivers/devfreq/governor_passive.c:95
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
```
**Symbols:**

```
ffffffff81859620-ffffffff818596d1: update_devfreq_passive (STB_LOCAL)
ffffffff8185986b-ffffffff81859884: update_devfreq_passive.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int update_devfreq_passive(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/governor_passive.c (0)
Location: drivers/devfreq/governor_passive.c:95
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
```
**Symbols:**

```
ffffffff818eb840-ffffffff818eb8f1: update_devfreq_passive (STB_LOCAL)
ffffffff818eba8b-ffffffff818ebaa4: update_devfreq_passive.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int update_devfreq_passive(struct devfreq *devfreq, long unsigned int freq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/devfreq/governor_passive.c (0)
Location: drivers/devfreq/governor_passive.c:95
Inline: False
Direct callers:
  - drivers/devfreq/governor_passive.c:devfreq_passive_notifier_call
```
**Symbols:**

```
ffffffff8190c8c0-ffffffff8190c971: update_devfreq_passive (STB_LOCAL)
ffffffff8190cb0b-ffffffff8190cb24: update_devfreq_passive.cold (STB_LOCAL)
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
