# Function: <code>labelset_next_stale</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8138dd0c)
Location: security/apparmor/label.c:1936
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813c8b0c)
Location: security/apparmor/label.c:1956
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813e0124)
Location: security/apparmor/label.c:1994
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff813ef5f2)
Location: security/apparmor/label.c:1972
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81417412)
Location: security/apparmor/label.c:1972
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81449882)
Location: security/apparmor/label.c:1985
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81466812)
Location: security/apparmor/label.c:1986
Inline: True
Inline callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814917dc)
Location: security/apparmor/label.c:1982
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814ab70c)
Location: security/apparmor/label.c:2011
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct aa_label *labelset_next_stale(struct aa_labelset *ls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81508390)
Location: security/apparmor/label.c:2008
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
ffffffff81508390-ffffffff81508449: labelset_next_stale (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct aa_label *labelset_next_stale(struct aa_labelset *ls);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff81525350)
Location: security/apparmor/label.c:2008
Inline: False
Direct callers:
  - security/apparmor/label.c:__aa_labelset_update_subtree
  - security/apparmor/label.c:__aa_labelset_update_subtree
```
**Symbols:**

```
ffffffff81525350-ffffffff81525409: labelset_next_stale (STB_LOCAL)
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
In security/apparmor/label.c (ffffffff8152cf93)
Location: security/apparmor/label.c:2008
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
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
In security/apparmor/label.c (ffffffff8158b383)
Location: security/apparmor/label.c:2008
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
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
In security/apparmor/label.c (ffffffff8162c8ee)
Location: security/apparmor/label.c:2018
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
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
In security/apparmor/label.c (ffffffff816e139e)
Location: security/apparmor/label.c:2012
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
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
In security/apparmor/label.c (ffffffff8171a99e)
Location: security/apparmor/label.c:2012
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
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
In security/apparmor/label.c (ffffffff8175944e)
Location: security/apparmor/label.c:2018
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffff8000105a2a90)
Location: security/apparmor/label.c:2011
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c0752d9c)
Location: security/apparmor/label.c:2011
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (c00000000071da90)
Location: security/apparmor/label.c:2011
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffe0003ed0c0)
Location: security/apparmor/label.c:2011
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814a3cec)
Location: security/apparmor/label.c:2011
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8149470c)
Location: security/apparmor/label.c:2011
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff8149fd8c)
Location: security/apparmor/label.c:2011
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/apparmor/label.c (ffffffff814b83bc)
Location: security/apparmor/label.c:2011
Inline: True
Inline callers:
  - security/apparmor/label.c:__labelset_update
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
