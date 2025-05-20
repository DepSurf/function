# Function: <code>selinux_is_genfs_special_handling</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81448eec)
Location: security/selinux/hooks.c:494
Inline: True
Inline callers:
  - security/selinux/hooks.c:sb_finish_set_opts
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
In security/selinux/hooks.c (ffffffff81462a7c)
Location: security/selinux/hooks.c:496
Inline: True
Inline callers:
  - security/selinux/hooks.c:sb_finish_set_opts
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
In security/selinux/hooks.c (ffffffff814b30b0)
Location: security/selinux/hooks.c:445
Inline: True
Direct callers:
  - security/selinux/hooks.c:sb_finish_set_opts
```
**Symbols:**

```
ffffffff814b30b0-ffffffff814b3199: selinux_is_genfs_special_handling.isra.0 (STB_LOCAL)
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
In security/selinux/hooks.c (ffffffff814cff60)
Location: security/selinux/hooks.c:446
Inline: True
Direct callers:
  - security/selinux/hooks.c:sb_finish_set_opts
```
**Symbols:**

```
ffffffff814cff60-ffffffff814d004f: selinux_is_genfs_special_handling.isra.0 (STB_LOCAL)
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
In security/selinux/hooks.c (ffffffff814dad0d)
Location: security/selinux/hooks.c:475
Inline: True
Inline callers:
  - security/selinux/hooks.c:sb_finish_set_opts
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
In security/selinux/hooks.c (ffffffff81533bf5)
Location: security/selinux/hooks.c:452
Inline: True
Inline callers:
  - security/selinux/hooks.c:sb_finish_set_opts
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
In security/selinux/hooks.c (ffffffff815ca408)
Location: security/selinux/hooks.c:436
Inline: True
Inline callers:
  - security/selinux/hooks.c:sb_finish_set_opts
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
In security/selinux/hooks.c (ffffffff8167764e)
Location: security/selinux/hooks.c:438
Inline: True
Inline callers:
  - security/selinux/hooks.c:sb_finish_set_opts
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
In security/selinux/hooks.c (ffffffff816af93b)
Location: security/selinux/hooks.c:430
Inline: True
Inline callers:
  - security/selinux/hooks.c:sb_finish_set_opts
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
In security/selinux/hooks.c (ffffffff816ec8ab)
Location: security/selinux/hooks.c:471
Inline: True
Inline callers:
  - security/selinux/hooks.c:sb_finish_set_opts
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
In security/selinux/hooks.c (ffff800010550954)
Location: security/selinux/hooks.c:496
Inline: True
Inline callers:
  - security/selinux/hooks.c:sb_finish_set_opts
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
In security/selinux/hooks.c (c0703428)
Location: security/selinux/hooks.c:496
Inline: True
Inline callers:
  - security/selinux/hooks.c:sb_finish_set_opts
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
In security/selinux/hooks.c (c0000000006a61d0)
Location: security/selinux/hooks.c:496
Inline: True
Inline callers:
  - security/selinux/hooks.c:sb_finish_set_opts
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
In security/selinux/hooks.c (ffffffe0003a9e28)
Location: security/selinux/hooks.c:496
Inline: True
Inline callers:
  - security/selinux/hooks.c:sb_finish_set_opts
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
In security/selinux/hooks.c (ffffffff8145b05c)
Location: security/selinux/hooks.c:496
Inline: True
Inline callers:
  - security/selinux/hooks.c:sb_finish_set_opts
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
In security/selinux/hooks.c (ffffffff8144ba8c)
Location: security/selinux/hooks.c:496
Inline: True
Inline callers:
  - security/selinux/hooks.c:sb_finish_set_opts
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
In security/selinux/hooks.c (ffffffff814570fc)
Location: security/selinux/hooks.c:496
Inline: True
Inline callers:
  - security/selinux/hooks.c:sb_finish_set_opts
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
In security/selinux/hooks.c (ffffffff8146c088)
Location: security/selinux/hooks.c:496
Inline: True
Inline callers:
  - security/selinux/hooks.c:sb_finish_set_opts
```
</details>
</li>
</ul>

## Differences
