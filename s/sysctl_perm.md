# Function: <code>sysctl_perm</code>

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
In fs/proc/proc_sysctl.c (ffffffff81284d12)
Location: fs/proc/proc_sysctl.c:417
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
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
In fs/proc/proc_sysctl.c (ffffffff812b1dd2)
Location: fs/proc/proc_sysctl.c:417
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
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
In fs/proc/proc_sysctl.c (ffffffff812c77e2)
Location: fs/proc/proc_sysctl.c:417
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sysctl_perm(struct ctl_table_header *head, struct ctl_table *table, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812d3e30)
Location: fs/proc/proc_sysctl.c:444
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff812d3e30-ffffffff812d3e9d: sysctl_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sysctl_perm(struct ctl_table_header *head, struct ctl_table *table, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff812f8660)
Location: fs/proc/proc_sysctl.c:445
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff812f8660-ffffffff812f86d0: sysctl_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sysctl_perm(struct ctl_table_header *head, struct ctl_table *table, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81325760)
Location: fs/proc/proc_sysctl.c:445
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff81325760-ffffffff813257cd: sysctl_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sysctl_perm(struct ctl_table_header *head, struct ctl_table *table, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8133c900)
Location: fs/proc/proc_sysctl.c:445
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff8133c900-ffffffff8133c96d: sysctl_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int sysctl_perm(struct ctl_table_header *head, struct ctl_table *table, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81364b90)
Location: fs/proc/proc_sysctl.c:450
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff81364b90-ffffffff81364c01: sysctl_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int sysctl_perm(struct ctl_table_header *head, struct ctl_table *table, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff8137ce20)
Location: fs/proc/proc_sysctl.c:450
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff8137ce20-ffffffff8137ce91: sysctl_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sysctl_perm(struct ctl_table_header *head, struct ctl_table *table, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813c6850)
Location: fs/proc/proc_sysctl.c:418
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
```
**Symbols:**

```
ffffffff813c6850-ffffffff813c68c1: sysctl_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sysctl_perm(struct ctl_table_header *head, struct ctl_table *table, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813d87f0)
Location: fs/proc/proc_sysctl.c:419
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff813d87f0-ffffffff813d8861: sysctl_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sysctl_perm(struct ctl_table_header *head, struct ctl_table *table, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff813df6c0)
Location: fs/proc/proc_sysctl.c:414
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff813df6c0-ffffffff813df731: sysctl_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sysctl_perm(struct ctl_table_header *head, struct ctl_table *table, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81431070)
Location: fs/proc/proc_sysctl.c:414
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff81431070-ffffffff814310e1: sysctl_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sysctl_perm(struct ctl_table_header *head, struct ctl_table *table, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff814ab080)
Location: fs/proc/proc_sysctl.c:439
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff814ab080-ffffffff814ab0f6: sysctl_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sysctl_perm(struct ctl_table_header *head, struct ctl_table *table, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81540f10)
Location: fs/proc/proc_sysctl.c:432
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff81540f10-ffffffff81540f86: sysctl_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sysctl_perm(struct ctl_table_header *head, struct ctl_table *table, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815792b0)
Location: fs/proc/proc_sysctl.c:426
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff815792b0-ffffffff81579328: sysctl_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sysctl_perm(struct ctl_table_header *head, struct ctl_table *table, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff815b1ae0)
Location: fs/proc/proc_sysctl.c:428
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff815b1ae0-ffffffff815b1b58: sysctl_perm (STB_LOCAL)
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
int sysctl_perm(struct ctl_table_header *head, struct ctl_table *table, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffff8000104497f0)
Location: fs/proc/proc_sysctl.c:450
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffff8000104497f0-ffff8000104498a0: sysctl_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sysctl_perm(struct ctl_table_header *head, struct ctl_table *table, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c060ee30)
Location: fs/proc/proc_sysctl.c:450
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
c060ee30-c060eeb0: sysctl_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int sysctl_perm(struct ctl_table_header *head, struct ctl_table *table, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (c000000000560820)
Location: fs/proc/proc_sysctl.c:450
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
c000000000560820-c0000000005608e8: sysctl_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int sysctl_perm(struct ctl_table_header *head, struct ctl_table *table, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffe0002df11a)
Location: fs/proc/proc_sysctl.c:450
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffe0002df11a-ffffffe0002df188: sysctl_perm (STB_LOCAL)
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
int sysctl_perm(struct ctl_table_header *head, struct ctl_table *table, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81375400)
Location: fs/proc/proc_sysctl.c:450
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff81375400-ffffffff81375471: sysctl_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int sysctl_perm(struct ctl_table_header *head, struct ctl_table *table, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81365ed0)
Location: fs/proc/proc_sysctl.c:450
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff81365ed0-ffffffff81365f41: sysctl_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int sysctl_perm(struct ctl_table_header *head, struct ctl_table *table, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81372ed0)
Location: fs/proc/proc_sysctl.c:450
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff81372ed0-ffffffff81372f41: sysctl_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int sysctl_perm(struct ctl_table_header *head, struct ctl_table *table, int op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff81386a20)
Location: fs/proc/proc_sysctl.c:450
Inline: False
Direct callers:
  - fs/proc/proc_sysctl.c:proc_sys_permission
  - fs/proc/proc_sysctl.c:proc_sys_call_handler
```
**Symbols:**

```
ffffffff81386a20-ffffffff81386a91: sysctl_perm (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
