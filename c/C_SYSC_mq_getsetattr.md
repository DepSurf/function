# Function: <code>C_SYSC_mq_getsetattr</code>

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
In ipc/compat_mq.c (ffffffff8132e771)
Location: ipc/compat_mq.c:112
Inline: True
Inline callers:
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
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
In ipc/compat_mq.c (ffffffff81363401)
Location: ipc/compat_mq.c:112
Inline: True
Inline callers:
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
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
In ipc/compat_mq.c (ffffffff81379bd1)
Location: ipc/compat_mq.c:112
Inline: True
Inline callers:
  - ipc/compat_mq.c:compat_SyS_mq_getsetattr
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int C_SYSC_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr *u_mqstat, struct compat_mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8138ce80)
Location: ipc/mqueue.c:1531
Inline: False
Direct callers:
  - ipc/mqueue.c:compat_SyS_mq_getsetattr
```
**Symbols:**

```
ffffffff8138ce80-ffffffff8138cfc6: C_SYSC_mq_getsetattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int C_SYSC_mq_getsetattr(mqd_t mqdes, const struct compat_mq_attr *u_mqstat, struct compat_mq_attr *u_omqstat);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813b2230)
Location: ipc/mqueue.c:1531
Inline: False
Direct callers:
  - ipc/mqueue.c:compat_SyS_mq_getsetattr
```
**Symbols:**

```
ffffffff813b2230-ffffffff813b2376: C_SYSC_mq_getsetattr (STB_LOCAL)
```
</details>
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
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
