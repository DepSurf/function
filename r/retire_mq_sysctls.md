# Function: <code>retire_mq_sysctls</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void retire_mq_sysctls(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mq_sysctl.c (ffffffff815a3960)
Location: ipc/mq_sysctl.c:123
Inline: False
Direct callers:
  - ipc/namespace.c:free_ipc
```
**Symbols:**

```
ffffffff815a3960-ffffffff815a399e: retire_mq_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void retire_mq_sysctls(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mq_sysctl.c (ffffffff8164d5e0)
Location: ipc/mq_sysctl.c:123
Inline: False
Direct callers:
  - ipc/mqueue.c:init_mqueue_fs
  - ipc/namespace.c:free_ipc
```
**Symbols:**

```
ffffffff8164d5e0-ffffffff8164d61e: retire_mq_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void retire_mq_sysctls(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mq_sysctl.c (ffffffff81685d80)
Location: ipc/mq_sysctl.c:123
Inline: False
Direct callers:
  - ipc/mqueue.c:init_mqueue_fs
  - ipc/namespace.c:free_ipc
```
**Symbols:**

```
ffffffff81685d80-ffffffff81685dbe: retire_mq_sysctls (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void retire_mq_sysctls(struct ipc_namespace *ns);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mq_sysctl.c (ffffffff816c21a0)
Location: ipc/mq_sysctl.c:125
Inline: False
Direct callers:
  - ipc/mqueue.c:init_mqueue_fs
  - ipc/namespace.c:free_ipc
```
**Symbols:**

```
ffffffff816c21a0-ffffffff816c21de: retire_mq_sysctls (STB_GLOBAL)
```
</details>
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
