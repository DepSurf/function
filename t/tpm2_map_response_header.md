# Function: <code>tpm2_map_response_header</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (ffffffff815bc6ce)
Location: drivers/char/tpm/tpm2-space.c:332
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff81622b6e)
Location: drivers/char/tpm/tpm2-space.c:332
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff8165c96f)
Location: drivers/char/tpm/tpm2-space.c:335
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff81679cdf)
Location: drivers/char/tpm/tpm2-space.c:333
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff816b03ff)
Location: drivers/char/tpm/tpm2-space.c:369
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff816d30ff)
Location: drivers/char/tpm/tpm2-space.c:369
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:374
Inline: True
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
ffffffff81786b50-ffffffff81786ca1: tpm2_map_response_header.constprop.0 (STB_LOCAL)
ffffffff81787704-ffffffff81787724: tpm2_map_response_header.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/tpm/tpm2-space.c (0)
Location: drivers/char/tpm/tpm2-space.c:374
Inline: True
Direct callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
**Symbols:**

```
ffffffff8179dc60-ffffffff8179ddb1: tpm2_map_response_header.constprop.0 (STB_LOCAL)
ffffffff81c0a74b-ffffffff81c0a76b: tpm2_map_response_header.constprop.0.cold (STB_LOCAL)
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
In drivers/char/tpm/tpm2-space.c (ffffffff81780f05)
Location: drivers/char/tpm/tpm2-space.c:374
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff818074bc)
Location: drivers/char/tpm/tpm2-space.c:374
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff819470dc)
Location: drivers/char/tpm/tpm2-space.c:374
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff81aaa425)
Location: drivers/char/tpm/tpm2-space.c:374
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff81af5c45)
Location: drivers/char/tpm/tpm2-space.c:374
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff81b49235)
Location: drivers/char/tpm/tpm2-space.c:374
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffff8000108bdd9c)
Location: drivers/char/tpm/tpm2-space.c:369
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (c09b7188)
Location: drivers/char/tpm/tpm2-space.c:369
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (c00000000095fdf4)
Location: drivers/char/tpm/tpm2-space.c:369
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffe00057026a)
Location: drivers/char/tpm/tpm2-space.c:369
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff81698b4f)
Location: drivers/char/tpm/tpm2-space.c:369
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff8167653f)
Location: drivers/char/tpm/tpm2-space.c:369
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff816c6dbf)
Location: drivers/char/tpm/tpm2-space.c:369
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
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
In drivers/char/tpm/tpm2-space.c (ffffffff816e12af)
Location: drivers/char/tpm/tpm2-space.c:369
Inline: True
Inline callers:
  - drivers/char/tpm/tpm2-space.c:tpm2_commit_space
```
</details>
</li>
</ul>

## Differences
