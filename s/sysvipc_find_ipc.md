# Function: <code>sysvipc_find_ipc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct kern_ipc_perm *sysvipc_find_ipc(struct ipc_ids *ids, loff_t pos, loff_t *new_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813247b0)
Location: ipc/util.c:746
Inline: False
Direct callers:
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:sysvipc_proc_start
```
**Symbols:**

```
ffffffff813247b0-ffffffff813248bc: sysvipc_find_ipc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct kern_ipc_perm *sysvipc_find_ipc(struct ipc_ids *ids, loff_t pos, loff_t *new_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813593a0)
Location: ipc/util.c:741
Inline: False
Direct callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
```
**Symbols:**

```
ffffffff813593a0-ffffffff813594ac: sysvipc_find_ipc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct kern_ipc_perm *sysvipc_find_ipc(struct ipc_ids *ids, loff_t pos, loff_t *new_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8136f890)
Location: ipc/util.c:741
Inline: False
Direct callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
```
**Symbols:**

```
ffffffff8136f890-ffffffff8136f9a0: sysvipc_find_ipc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *sysvipc_find_ipc(struct ipc_ids *ids, loff_t pos, loff_t *new_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81382dc0)
Location: ipc/util.c:687
Inline: True
Direct callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
```
**Symbols:**

```
ffffffff81382dc0-ffffffff81382e93: sysvipc_find_ipc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *sysvipc_find_ipc(struct ipc_ids *ids, loff_t pos, loff_t *new_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813a6d70)
Location: ipc/util.c:753
Inline: True
Direct callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
```
**Symbols:**

```
ffffffff813a6d70-ffffffff813a6e43: sysvipc_find_ipc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *sysvipc_find_ipc(struct ipc_ids *ids, loff_t pos, loff_t *new_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813d5f80)
Location: ipc/util.c:764
Inline: True
Direct callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
```
**Symbols:**

```
ffffffff813d5f80-ffffffff813d6053: sysvipc_find_ipc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *sysvipc_find_ipc(struct ipc_ids *ids, loff_t pos, loff_t *new_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff813f0640)
Location: ipc/util.c:725
Inline: True
Direct callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
```
**Symbols:**

```
ffffffff813f0640-ffffffff813f0713: sysvipc_find_ipc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *sysvipc_find_ipc(struct ipc_ids *ids, loff_t pos, loff_t *new_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8141c960)
Location: ipc/util.c:754
Inline: True
Direct callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
```
**Symbols:**

```
ffffffff8141c960-ffffffff8141ca25: sysvipc_find_ipc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *sysvipc_find_ipc(struct ipc_ids *ids, loff_t pos, loff_t *new_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814367b0)
Location: ipc/util.c:754
Inline: True
Direct callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
```
**Symbols:**

```
ffffffff814367b0-ffffffff81436875: sysvipc_find_ipc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct kern_ipc_perm *sysvipc_find_ipc(struct ipc_ids *ids, loff_t pos, loff_t *new_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814864c0)
Location: ipc/util.c:754
Inline: False
Direct callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
```
**Symbols:**

```
ffffffff814864c0-ffffffff81486591: sysvipc_find_ipc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct kern_ipc_perm *sysvipc_find_ipc(struct ipc_ids *ids, loff_t pos, loff_t *new_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814a3ac0)
Location: ipc/util.c:754
Inline: False
Direct callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
```
**Symbols:**

```
ffffffff814a3ac0-ffffffff814a3b80: sysvipc_find_ipc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct kern_ipc_perm *sysvipc_find_ipc(struct ipc_ids *ids, loff_t pos, loff_t *new_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff814a9ac0)
Location: ipc/util.c:754
Inline: False
Direct callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
```
**Symbols:**

```
ffffffff814a9ac0-ffffffff814a9b80: sysvipc_find_ipc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct kern_ipc_perm *sysvipc_find_ipc(struct ipc_ids *ids, loff_t pos, loff_t *new_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81501e50)
Location: ipc/util.c:788
Inline: False
Direct callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
```
**Symbols:**

```
ffffffff81501e50-ffffffff81501ee5: sysvipc_find_ipc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct kern_ipc_perm *sysvipc_find_ipc(struct ipc_ids *ids, loff_t pos, loff_t *new_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff815932c0)
Location: ipc/util.c:788
Inline: False
Direct callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
```
**Symbols:**

```
ffffffff815932c0-ffffffff81593367: sysvipc_find_ipc (STB_LOCAL)
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
In ipc/util.c (ffffffff8163befe)
Location: ipc/util.c:800
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
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
In ipc/util.c (ffffffff816743ae)
Location: ipc/util.c:800
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
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
In ipc/util.c (ffffffff816b076e)
Location: ipc/util.c:800
Inline: True
Inline callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *sysvipc_find_ipc(struct ipc_ids *ids, loff_t pos, loff_t *new_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffff80001051cef8)
Location: ipc/util.c:754
Inline: True
Direct callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
```
**Symbols:**

```
ffff80001051cef8-ffff80001051d014: sysvipc_find_ipc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *sysvipc_find_ipc(struct ipc_ids *ids, loff_t pos, loff_t *new_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (c06d906c)
Location: ipc/util.c:754
Inline: True
Direct callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
```
**Symbols:**

```
c06d906c-c06d9160: sysvipc_find_ipc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *sysvipc_find_ipc(struct ipc_ids *ids, loff_t pos, loff_t *new_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (c000000000665af0)
Location: ipc/util.c:754
Inline: True
Direct callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
  - ipc/util.c:sysvipc_proc_next
```
**Symbols:**

```
c000000000665af0-c000000000665c40: sysvipc_find_ipc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *sysvipc_find_ipc(struct ipc_ids *ids, loff_t pos, loff_t *new_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffe00038464e)
Location: ipc/util.c:754
Inline: True
Direct callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
```
**Symbols:**

```
ffffffe00038464e-ffffffe0003846fa: sysvipc_find_ipc (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *sysvipc_find_ipc(struct ipc_ids *ids, loff_t pos, loff_t *new_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8142ed90)
Location: ipc/util.c:754
Inline: True
Direct callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
```
**Symbols:**

```
ffffffff8142ed90-ffffffff8142ee55: sysvipc_find_ipc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *sysvipc_find_ipc(struct ipc_ids *ids, loff_t pos, loff_t *new_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8141f810)
Location: ipc/util.c:754
Inline: True
Direct callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
```
**Symbols:**

```
ffffffff8141f810-ffffffff8141f8d5: sysvipc_find_ipc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *sysvipc_find_ipc(struct ipc_ids *ids, loff_t pos, loff_t *new_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff8142af30)
Location: ipc/util.c:754
Inline: True
Direct callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
```
**Symbols:**

```
ffffffff8142af30-ffffffff8142aff5: sysvipc_find_ipc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct kern_ipc_perm *sysvipc_find_ipc(struct ipc_ids *ids, loff_t pos, loff_t *new_pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In ipc/util.c (ffffffff81441e40)
Location: ipc/util.c:754
Inline: True
Direct callers:
  - ipc/util.c:sysvipc_proc_start
  - ipc/util.c:sysvipc_proc_next
```
**Symbols:**

```
ffffffff81441e40-ffffffff81441f12: sysvipc_find_ipc (STB_LOCAL)
```
</details>
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
