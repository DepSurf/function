# Function: <code>match_opt_prefix</code>

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
<details>
<summary>In <code>5.0</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:435
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
```
In security/smack/smack_lsm.c (ffffffff81435f34)
Location: security/smack/smack_lsm.c:72
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:436
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
```
In security/smack/smack_lsm.c (ffffffff81463b81)
Location: security/smack/smack_lsm.c:73
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:438
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
```
In security/smack/smack_lsm.c (ffffffff8147d951)
Location: security/smack/smack_lsm.c:73
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int match_opt_prefix(char *s, int l, char **arg);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b1e20)
Location: security/selinux/hooks.c:387
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
```
In security/smack/smack_lsm.c (ffffffff814d3010)
Location: security/smack/smack_lsm.c:70
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff814b1e20-ffffffff814b1edd: match_opt_prefix.constprop.0 (STB_LOCAL)
ffffffff814d3010-ffffffff814d30c9: match_opt_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline, Transformation ⚠️</summary>

```c
int match_opt_prefix(char *s, int l, char **arg);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff814cf1a0)
Location: security/selinux/hooks.c:388
Inline: True
Direct callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
```
In security/smack/smack_lsm.c (ffffffff814f02c0)
Location: security/smack/smack_lsm.c:70
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff814cf1a0-ffffffff814cf25d: match_opt_prefix.constprop.0 (STB_LOCAL)
ffffffff814f02c0-ffffffff814f0379: match_opt_prefix (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:417
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
```
In security/smack/smack_lsm.c (ffffffff814fa32c)
Location: security/smack/smack_lsm.c:70
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:394
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
```
In security/smack/smack_lsm.c (ffffffff81554f27)
Location: security/smack/smack_lsm.c:70
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:378
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
```
In security/smack/smack_lsm.c (ffffffff815ee0b1)
Location: security/smack/smack_lsm.c:73
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:380
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
```
In security/smack/smack_lsm.c (ffffffff8169ddf1)
Location: security/smack/smack_lsm.c:74
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:376
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
```
In security/smack/smack_lsm.c (ffffffff816d438c)
Location: security/smack/smack_lsm.c:74
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:417
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
```
In security/smack/smack_lsm.c (ffffffff8171082c)
Location: security/smack/smack_lsm.c:84
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:438
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
```
In security/smack/smack_lsm.c (ffff80001056e6c0)
Location: security/smack/smack_lsm.c:73
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:438
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
```
In security/smack/smack_lsm.c (c0722068)
Location: security/smack/smack_lsm.c:73
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:438
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
```
In security/smack/smack_lsm.c (c0000000006d54c8)
Location: security/smack/smack_lsm.c:73
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a7744)
Location: security/selinux/hooks.c:438
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
```
In security/smack/smack_lsm.c (ffffffe0003c4732)
Location: security/smack/smack_lsm.c:73
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:438
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
```
In security/smack/smack_lsm.c (ffffffff81475f31)
Location: security/smack/smack_lsm.c:73
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:438
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
```
In security/smack/smack_lsm.c (ffffffff81466951)
Location: security/smack/smack_lsm.c:73
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:438
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
```
In security/smack/smack_lsm.c (ffffffff81471fd1)
Location: security/smack/smack_lsm.c:73
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:438
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
```
In security/smack/smack_lsm.c (ffffffff814898c1)
Location: security/smack/smack_lsm.c:73
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
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
