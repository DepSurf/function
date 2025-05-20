# Function: <code>audit_replace</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit.c (ffffffff8112b6f3)
Location: kernel/audit.c:810
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff811354ff)
Location: kernel/audit.c:950
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff8113676b)
Location: kernel/audit.c:1126
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff811430fb)
Location: kernel/audit.c:1126
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff81151a62)
Location: kernel/audit.c:1170
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff8115e717)
Location: kernel/audit.c:1167
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff8116ad30)
Location: kernel/audit.c:1161
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff81176bdb)
Location: kernel/audit.c:1159
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff81189455)
Location: kernel/audit.c:1187
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff811867e9)
Location: kernel/audit.c:1191
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff81186200)
Location: kernel/audit.c:1191
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff81186200-ffffffff8118637d: audit_replace.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff811ae5f0)
Location: kernel/audit.c:1213
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff811ae5f0-ffffffff811ae76d: audit_replace.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff811e0520)
Location: kernel/audit.c:1195
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff811e0520-ffffffff811e06d2: audit_replace.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff812262d0)
Location: kernel/audit.c:1193
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff812262d0-ffffffff81226482: audit_replace.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff8123c8b0)
Location: kernel/audit.c:1193
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff8123c8b0-ffffffff8123ca62: audit_replace.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/audit.c (ffffffff812567c0)
Location: kernel/audit.c:1204
Inline: True
Direct callers:
  - kernel/audit.c:audit_receive_msg
  - kernel/audit.c:audit_receive_msg
```
**Symbols:**

```
ffffffff812567c0-ffffffff81256972: audit_replace.isra.0 (STB_LOCAL)
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
In kernel/audit.c (ffff8000101ebb8c)
Location: kernel/audit.c:1159
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (c042b790)
Location: kernel/audit.c:1159
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (c00000000025d1b8)
Location: kernel/audit.c:1159
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffe0001602e0)
Location: kernel/audit.c:1159
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff8116f1fb)
Location: kernel/audit.c:1159
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff8116239b)
Location: kernel/audit.c:1159
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff8116cfcb)
Location: kernel/audit.c:1159
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
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
In kernel/audit.c (ffffffff8117a7a1)
Location: kernel/audit.c:1159
Inline: True
Inline callers:
  - kernel/audit.c:audit_receive_msg
```
</details>
</li>
</ul>

## Differences
