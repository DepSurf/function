# Function: <code>new_task_smack</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct task_smack *new_task_smack(struct smack_known *task, struct smack_known *forked, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81361680)
Location: security/smack/smack_lsm.c:317
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
  - security/smack/smack_lsm.c:smack_cred_prepare
```
**Symbols:**

```
ffffffff81361680-ffffffff81361709: new_task_smack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct task_smack *new_task_smack(struct smack_known *task, struct smack_known *forked, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81397410)
Location: security/smack/smack_lsm.c:317
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
```
**Symbols:**

```
ffffffff81397410-ffffffff81397499: new_task_smack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct task_smack *new_task_smack(struct smack_known *task, struct smack_known *forked, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff813ae010)
Location: security/smack/smack_lsm.c:317
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
```
**Symbols:**

```
ffffffff813ae010-ffffffff813ae099: new_task_smack (STB_LOCAL)
```
</details>
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct task_smack *new_task_smack(struct smack_known *task, struct smack_known *forked, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8141a130)
Location: security/smack/smack_lsm.c:318
Inline: False
Direct callers:
  - security/smack/smack_lsm.c:smack_init
  - security/smack/smack_lsm.c:smack_cred_prepare
  - security/smack/smack_lsm.c:smack_cred_alloc_blank
```
**Symbols:**

```
ffffffff8141a130-ffffffff8141a1b9: new_task_smack (STB_LOCAL)
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
</ul>
