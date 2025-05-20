# Function: <code>proc_ipc_dointvec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int proc_ipc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/ipc_sysctl.c (ffffffff8132bb70)
Location: ipc/ipc_sysctl.c:30
Inline: False
```
**Symbols:**

```
ffffffff8132bb70-ffffffff8132bc08: proc_ipc_dointvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int proc_ipc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/ipc_sysctl.c (ffffffff81360800)
Location: ipc/ipc_sysctl.c:30
Inline: False
```
**Symbols:**

```
ffffffff81360800-ffffffff81360898: proc_ipc_dointvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int proc_ipc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/ipc_sysctl.c (ffffffff81377020)
Location: ipc/ipc_sysctl.c:30
Inline: False
```
**Symbols:**

```
ffffffff81377020-ffffffff813770b8: proc_ipc_dointvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int proc_ipc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/ipc_sysctl.c (ffffffff8138abb0)
Location: ipc/ipc_sysctl.c:30
Inline: False
```
**Symbols:**

```
ffffffff8138abb0-ffffffff8138ac48: proc_ipc_dointvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int proc_ipc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/ipc_sysctl.c (ffffffff813aff70)
Location: ipc/ipc_sysctl.c:30
Inline: False
```
**Symbols:**

```
ffffffff813aff70-ffffffff813b0008: proc_ipc_dointvec (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int proc_ipc_dointvec(struct ctl_table *table, int write, void *buffer, size_t *lenp, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/ipc_sysctl.c (ffffffff813e00e0)
Location: ipc/ipc_sysctl.c:30
Inline: False
```
**Symbols:**

```
ffffffff813e00e0-ffffffff813e0178: proc_ipc_dointvec (STB_LOCAL)
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
In ipc/ipc_sysctl.c (ffffffff813fa764)
Location: ipc/ipc_sysctl.c:30
Inline: True
Inline callers:
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
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
In ipc/ipc_sysctl.c (ffffffff81426b44)
Location: ipc/ipc_sysctl.c:26
Inline: True
Inline callers:
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
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
In ipc/ipc_sysctl.c (ffffffff81440884)
Location: ipc/ipc_sysctl.c:26
Inline: True
Inline callers:
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
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
In ipc/ipc_sysctl.c (ffffffff81491644)
Location: ipc/ipc_sysctl.c:26
Inline: True
Inline callers:
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
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
In ipc/ipc_sysctl.c (ffffffff814aee84)
Location: ipc/ipc_sysctl.c:26
Inline: True
Inline callers:
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
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
In ipc/ipc_sysctl.c (ffffffff814b4cba)
Location: ipc/ipc_sysctl.c:26
Inline: True
Inline callers:
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
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
In ipc/ipc_sysctl.c (ffffffff8150d36a)
Location: ipc/ipc_sysctl.c:26
Inline: True
Inline callers:
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In ipc/ipc_sysctl.c (ffff800010528dfc)
Location: ipc/ipc_sysctl.c:26
Inline: True
Inline callers:
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
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
In ipc/ipc_sysctl.c (c06e21f4)
Location: ipc/ipc_sysctl.c:26
Inline: True
Inline callers:
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
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
In ipc/ipc_sysctl.c (c00000000067434c)
Location: ipc/ipc_sysctl.c:26
Inline: True
Inline callers:
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
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
In ipc/ipc_sysctl.c (ffffffe00038c228)
Location: ipc/ipc_sysctl.c:26
Inline: True
Inline callers:
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
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
In ipc/ipc_sysctl.c (ffffffff81438e64)
Location: ipc/ipc_sysctl.c:26
Inline: True
Inline callers:
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
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
In ipc/ipc_sysctl.c (ffffffff814298d4)
Location: ipc/ipc_sysctl.c:26
Inline: True
Inline callers:
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
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
In ipc/ipc_sysctl.c (ffffffff81435004)
Location: ipc/ipc_sysctl.c:26
Inline: True
Inline callers:
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
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
In ipc/ipc_sysctl.c (ffffffff8144c144)
Location: ipc/ipc_sysctl.c:26
Inline: True
Inline callers:
  - ipc/ipc_sysctl.c:proc_ipc_sem_dointvec
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
</ul>
