# Function: <code>smack_parse_opts_str</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int smack_parse_opts_str(char *options, struct security_mnt_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813606f0)
Location: security/smack/smack_lsm.c:626
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_kern_mount
```
**Symbols:**

```
ffffffff813606f0-ffffffff813609ab: smack_parse_opts_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int smack_parse_opts_str(char *options, struct security_mnt_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81397690)
Location: security/smack/smack_lsm.c:626
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_kern_mount
```
**Symbols:**

```
ffffffff81397690-ffffffff8139796e: smack_parse_opts_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int smack_parse_opts_str(char *options, struct security_mnt_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813ae270)
Location: security/smack/smack_lsm.c:626
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_kern_mount
```
**Symbols:**

```
ffffffff813ae270-ffffffff813ae54e: smack_parse_opts_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int smack_parse_opts_str(char *options, struct security_mnt_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813c31a0)
Location: security/smack/smack_lsm.c:591
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_kern_mount
```
**Symbols:**

```
ffffffff813c31a0-ffffffff813c3469: smack_parse_opts_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int smack_parse_opts_str(char *options, struct security_mnt_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813e9460)
Location: security/smack/smack_lsm.c:591
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_kern_mount
```
**Symbols:**

```
ffffffff813e9460-ffffffff813e972f: smack_parse_opts_str (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int smack_parse_opts_str(char *options, struct security_mnt_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/smack/smack_lsm.c (0)
Location: security/smack/smack_lsm.c:623
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_sb_kern_mount
```
**Symbols:**

```
ffffffff8141a390-ffffffff8141a64f: smack_parse_opts_str (STB_LOCAL)
ffffffff8141cff1-ffffffff8141d01d: smack_parse_opts_str.cold.32 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
</ul>
