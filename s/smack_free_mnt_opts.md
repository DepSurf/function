# Function: <code>smack_free_mnt_opts</code>

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
void smack_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81435430)
Location: security/smack/smack_lsm.c:576
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff81435430-ffffffff81435474: smack_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void smack_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81462f20)
Location: security/smack/smack_lsm.c:576
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff81462f20-ffffffff81462f6a: smack_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void smack_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8147ccd0)
Location: security/smack/smack_lsm.c:576
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff8147ccd0-ffffffff8147cd1a: smack_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void smack_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814d5778)
Location: security/smack/smack_lsm.c:572
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff814d2770-ffffffff814d27bc: smack_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void smack_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f30a8)
Location: security/smack/smack_lsm.c:572
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff814efc60-ffffffff814efcac: smack_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void smack_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814fa3ea)
Location: security/smack/smack_lsm.c:555
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff814f6cd0-ffffffff814f6d1c: smack_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void smack_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81554fea)
Location: security/smack/smack_lsm.c:555
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff81551860-ffffffff815518ac: smack_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void smack_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff815ee188)
Location: security/smack/smack_lsm.c:558
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff815eb010-ffffffff815eb05d: smack_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void smack_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8169dec8)
Location: security/smack/smack_lsm.c:557
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff8169aee0-ffffffff8169af2d: smack_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void smack_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff816d4455)
Location: security/smack/smack_lsm.c:561
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff816d3720-ffffffff816d3736: smack_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void smack_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff817108f5)
Location: security/smack/smack_lsm.c:579
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff8170e920-ffffffff8170e943: smack_free_mnt_opts (STB_LOCAL)
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
void smack_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffff80001056dc40)
Location: security/smack/smack_lsm.c:576
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
**Symbols:**

```
ffff80001056dc40-ffff80001056dc94: smack_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void smack_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0721260)
Location: security/smack/smack_lsm.c:576
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
**Symbols:**

```
c0721260-c07212ac: smack_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void smack_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (c0000000006d3150)
Location: security/smack/smack_lsm.c:576
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
**Symbols:**

```
c0000000006d3150-c0000000006d31d0: smack_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void smack_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffe0003c242e)
Location: security/smack/smack_lsm.c:576
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffe0003c242e-ffffffe0003c248a: smack_free_mnt_opts (STB_LOCAL)
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
void smack_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814752b0)
Location: security/smack/smack_lsm.c:576
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff814752b0-ffffffff814752fa: smack_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void smack_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81465cd0)
Location: security/smack/smack_lsm.c:576
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff81465cd0-ffffffff81465d1a: smack_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void smack_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81471350)
Location: security/smack/smack_lsm.c:576
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff81471350-ffffffff8147139a: smack_free_mnt_opts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void smack_free_mnt_opts(void *mnt_opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81488c40)
Location: security/smack/smack_lsm.c:576
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_eat_lsm_opts
```
**Symbols:**

```
ffffffff81488c40-ffffffff81488c8a: smack_free_mnt_opts (STB_LOCAL)
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
