# Function: <code>selinux_sb_eat_lsm_opts</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
int selinux_sb_eat_lsm_opts(char *options, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81418550)
Location: security/selinux/hooks.c:2576
Inline: False
```
**Symbols:**

```
ffffffff81418550-ffffffff81418799: selinux_sb_eat_lsm_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int selinux_sb_eat_lsm_opts(char *options, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81446340)
Location: security/selinux/hooks.c:2620
Inline: False
```
**Symbols:**

```
ffffffff81446340-ffffffff81446570: selinux_sb_eat_lsm_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int selinux_sb_eat_lsm_opts(char *options, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145fed0)
Location: security/selinux/hooks.c:2622
Inline: False
```
**Symbols:**

```
ffffffff8145fed0-ffffffff81460100: selinux_sb_eat_lsm_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int selinux_sb_eat_lsm_opts(char *options, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b3fc0)
Location: security/selinux/hooks.c:2591
Inline: False
```
**Symbols:**

```
ffffffff814b3fc0-ffffffff814b418a: selinux_sb_eat_lsm_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int selinux_sb_eat_lsm_opts(char *options, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d1730)
Location: security/selinux/hooks.c:2599
Inline: False
```
**Symbols:**

```
ffffffff814d1730-ffffffff814d18fa: selinux_sb_eat_lsm_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int selinux_sb_eat_lsm_opts(char *options, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d7c20)
Location: security/selinux/hooks.c:2642
Inline: False
```
**Symbols:**

```
ffffffff814d7c20-ffffffff814d7e84: selinux_sb_eat_lsm_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int selinux_sb_eat_lsm_opts(char *options, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2635
Inline: False
```
**Symbols:**

```
ffffffff81531030-ffffffff8153134d: selinux_sb_eat_lsm_opts (STB_LOCAL)
ffffffff81cd3803-ffffffff81cd3826: selinux_sb_eat_lsm_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int selinux_sb_eat_lsm_opts(char *options, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2573
Inline: False
```
**Symbols:**

```
ffffffff815c7820-ffffffff815c7aea: selinux_sb_eat_lsm_opts (STB_LOCAL)
ffffffff81e86900-ffffffff81e8691b: selinux_sb_eat_lsm_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int selinux_sb_eat_lsm_opts(char *options, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2572
Inline: False
```
**Symbols:**

```
ffffffff816746d0-ffffffff816749a1: selinux_sb_eat_lsm_opts (STB_LOCAL)
ffffffff820733e9-ffffffff82073404: selinux_sb_eat_lsm_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int selinux_sb_eat_lsm_opts(char *options, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2551
Inline: False
```
**Symbols:**

```
ffffffff816acd40-ffffffff816ad00d: selinux_sb_eat_lsm_opts (STB_LOCAL)
ffffffff820f3016-ffffffff820f3031: selinux_sb_eat_lsm_opts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int selinux_sb_eat_lsm_opts(char *options, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2604
Inline: False
```
**Symbols:**

```
ffffffff816ea130-ffffffff816ea3f4: selinux_sb_eat_lsm_opts (STB_LOCAL)
ffffffff821d032a-ffffffff821d0345: selinux_sb_eat_lsm_opts.cold (STB_LOCAL)
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
int selinux_sb_eat_lsm_opts(char *options, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff80001054d560)
Location: security/selinux/hooks.c:2622
Inline: False
```
**Symbols:**

```
ffff80001054d560-ffff80001054d7fc: selinux_sb_eat_lsm_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int selinux_sb_eat_lsm_opts(char *options, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0706254)
Location: security/selinux/hooks.c:2622
Inline: False
```
**Symbols:**

```
c0706254-c07064c4: selinux_sb_eat_lsm_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int selinux_sb_eat_lsm_opts(char *options, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006ad920)
Location: security/selinux/hooks.c:2622
Inline: False
```
**Symbols:**

```
c0000000006ad920-c0000000006adc40: selinux_sb_eat_lsm_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int selinux_sb_eat_lsm_opts(char *options, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a7708)
Location: security/selinux/hooks.c:2622
Inline: False
```
**Symbols:**

```
ffffffe0003a7708-ffffffe0003a78f2: selinux_sb_eat_lsm_opts (STB_LOCAL)
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
int selinux_sb_eat_lsm_opts(char *options, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814584b0)
Location: security/selinux/hooks.c:2622
Inline: False
```
**Symbols:**

```
ffffffff814584b0-ffffffff814586e0: selinux_sb_eat_lsm_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int selinux_sb_eat_lsm_opts(char *options, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81448ee0)
Location: security/selinux/hooks.c:2622
Inline: False
```
**Symbols:**

```
ffffffff81448ee0-ffffffff81449110: selinux_sb_eat_lsm_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int selinux_sb_eat_lsm_opts(char *options, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81454550)
Location: security/selinux/hooks.c:2622
Inline: False
```
**Symbols:**

```
ffffffff81454550-ffffffff81454780: selinux_sb_eat_lsm_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int selinux_sb_eat_lsm_opts(char *options, void **mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8146ef30)
Location: security/selinux/hooks.c:2622
Inline: False
```
**Symbols:**

```
ffffffff8146ef30-ffffffff8146f160: selinux_sb_eat_lsm_opts (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
