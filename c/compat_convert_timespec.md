# Function: <code>compat_convert_timespec</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int compat_convert_timespec(struct timespec **kts, const void *cts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff811103a0)
Location: kernel/compat.c:193
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat_mq.c:compat_SyS_mq_timedsend
  - ipc/compat_mq.c:compat_SyS_mq_timedreceive
```
**Symbols:**

```
ffffffff811103a0-ffffffff81110452: compat_convert_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int compat_convert_timespec(struct timespec **kts, const void *cts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81117b00)
Location: kernel/compat.c:193
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat_mq.c:compat_SyS_mq_timedreceive
  - ipc/compat_mq.c:compat_SyS_mq_timedsend
```
**Symbols:**

```
ffffffff81117b00-ffffffff81117bb2: compat_convert_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int compat_convert_timespec(struct timespec **kts, const void *cts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff8111f220)
Location: kernel/compat.c:193
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_ipc
  - ipc/compat_mq.c:compat_SyS_mq_timedreceive
  - ipc/compat_mq.c:compat_SyS_mq_timedsend
```
**Symbols:**

```
ffffffff8111f220-ffffffff8111f2d2: compat_convert_timespec (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int compat_convert_timespec(struct timespec **kts, const void *cts);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/compat.c (ffffffff81120a00)
Location: kernel/compat.c:203
Inline: False
Direct callers:
  - ipc/compat.c:compat_SyS_ipc
```
**Symbols:**

```
ffffffff81120a00-ffffffff81120ab2: compat_convert_timespec (STB_GLOBAL)
```
</details>
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
</ul>
