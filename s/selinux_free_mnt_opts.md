# Function: <code>selinux_free_mnt_opts</code>

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
void selinux_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81415ff0)
Location: security/selinux/hooks.c:396
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffff81415ff0-ffffffff8141602b: selinux_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void selinux_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81443a50)
Location: security/selinux/hooks.c:397
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffff81443a50-ffffffff81443a90: selinux_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void selinux_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145d5a0)
Location: security/selinux/hooks.c:399
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffff8145d5a0-ffffffff8145d5e0: selinux_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void selinux_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b413c)
Location: security/selinux/hooks.c:353
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffff814b0700-ffffffff814b0742: selinux_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void selinux_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d18ac)
Location: security/selinux/hooks.c:354
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffff814cdaf0-ffffffff814cdb32: selinux_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void selinux_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d7e2e)
Location: security/selinux/hooks.c:383
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffff814d4210-ffffffff814d4252: selinux_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void selinux_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8153128a)
Location: security/selinux/hooks.c:360
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffff8152ced0-ffffffff8152cf12: selinux_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void selinux_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c7a81)
Location: security/selinux/hooks.c:349
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff815c3780-ffffffff815c3796: selinux_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void selinux_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81674938)
Location: security/selinux/hooks.c:351
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff816701d0-ffffffff816701e6: selinux_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void selinux_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816acfa4)
Location: security/selinux/hooks.c:347
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff816a87f0-ffffffff816a8806: selinux_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void selinux_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816ea366)
Location: security/selinux/hooks.c:383
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff816e2c20-ffffffff816e2c43: selinux_free_mnt_opts (STB_LOCAL)
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
void selinux_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff80001054a460)
Location: security/selinux/hooks.c:399
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffff80001054a460-ffff80001054a4ac: selinux_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void selinux_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c07002bc)
Location: security/selinux/hooks.c:399
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
c07002bc-c0700300: selinux_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void selinux_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a1e10)
Location: security/selinux/hooks.c:399
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
c0000000006a1e10-c0000000006a1e84: selinux_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void selinux_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a5016)
Location: security/selinux/hooks.c:399
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffe0003a5016-ffffffe0003a5068: selinux_free_mnt_opts (STB_LOCAL)
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
void selinux_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81455b80)
Location: security/selinux/hooks.c:399
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffff81455b80-ffffffff81455bc0: selinux_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void selinux_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814465c0)
Location: security/selinux/hooks.c:399
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffff814465c0-ffffffff81446600: selinux_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void selinux_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81451c20)
Location: security/selinux/hooks.c:399
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffff81451c20-ffffffff81451c60: selinux_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void selinux_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814689b0)
Location: security/selinux/hooks.c:399
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_sb_eat_lsm_opts
  - security/selinux/hooks.c:selinux_add_mnt_opt
```
**Symbols:**

```
ffffffff814689b0-ffffffff814689f0: selinux_free_mnt_opts (STB_LOCAL)
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
