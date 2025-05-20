# Function: <code>compat_SyS_mq_timedsend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int compat_SyS_mq_timedsend(long int mqdes, long int u_msg_ptr, long int msg_len, long int msg_prio, long int u_abs_timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat_mq.c (ffffffff8132e5b0)
Location: ipc/compat_mq.c:67
Inline: False
```
**Symbols:**

```
ffffffff8132e5b0-ffffffff8132e62d: compat_SyS_mq_timedsend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int compat_SyS_mq_timedsend(long int mqdes, long int u_msg_ptr, long int msg_len, long int msg_prio, long int u_abs_timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat_mq.c (ffffffff81363240)
Location: ipc/compat_mq.c:67
Inline: False
```
**Symbols:**

```
ffffffff81363240-ffffffff813632bd: compat_SyS_mq_timedsend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int compat_SyS_mq_timedsend(long int mqdes, long int u_msg_ptr, long int msg_len, long int msg_prio, long int u_abs_timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/compat_mq.c (ffffffff81379a10)
Location: ipc/compat_mq.c:67
Inline: False
```
**Symbols:**

```
ffffffff81379a10-ffffffff81379a8d: compat_SyS_mq_timedsend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int compat_SyS_mq_timedsend(long int mqdes, long int u_msg_ptr, long int msg_len, long int msg_prio, long int u_abs_timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff8138d6f0)
Location: ipc/mqueue.c:1487
Inline: False
```
**Symbols:**

```
ffffffff8138d6f0-ffffffff8138d793: compat_SyS_mq_timedsend (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int compat_SyS_mq_timedsend(long int mqdes, long int u_msg_ptr, long int msg_len, long int msg_prio, long int u_abs_timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/mqueue.c (ffffffff813b2b10)
Location: ipc/mqueue.c:1487
Inline: False
```
**Symbols:**

```
ffffffff813b2b10-ffffffff813b2bb3: compat_SyS_mq_timedsend (STB_GLOBAL)
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
</ul>
