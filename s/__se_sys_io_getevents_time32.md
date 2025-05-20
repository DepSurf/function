# Function: <code>__se_sys_io_getevents_time32</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff81329f2a)
Location: fs/aio.c:2159
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
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
In fs/aio.c (ffffffff8133cd8a)
Location: fs/aio.c:2175
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
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
In fs/aio.c (ffffffff8137615a)
Location: fs/aio.c:2182
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
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
In fs/aio.c (ffffffff8138416a)
Location: fs/aio.c:2180
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
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
In fs/aio.c (ffffffff8138adba)
Location: fs/aio.c:2177
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
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
In fs/aio.c (ffffffff813d807a)
Location: fs/aio.c:2295
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/aio.c (ffffffff814627ea)
Location: fs/aio.c:2319
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
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
In fs/aio.c (ffffffff814f2e6a)
Location: fs/aio.c:2320
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
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
In fs/aio.c (ffffffff81529c1a)
Location: fs/aio.c:2312
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
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
In fs/aio.c (ffffffff8155eaea)
Location: fs/aio.c:2355
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
```
</details>
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
In fs/aio.c (ffff8000103fc908)
Location: fs/aio.c:2175
Inline: True
Inline callers:
  - fs/aio.c:__arm64_sys_io_getevents_time32
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int __se_sys_io_getevents_time32(long int ctx_id, long int min_nr, long int nr, long int events, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c05d1bbc)
Location: fs/aio.c:2175
Inline: False
```
**Symbols:**

```
c05d1bbc-c05d1c8c: __se_sys_io_getevents_time32 (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int __se_sys_io_getevents_time32(long int ctx_id, long int min_nr, long int nr, long int events, long int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/aio.c (c0000000005055e0)
Location: fs/aio.c:2175
Inline: False
```
**Symbols:**

```
c0000000005055e0-c0000000005056dc: __se_sys_io_getevents_time32 (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In fs/aio.c (ffffffff8133536a)
Location: fs/aio.c:2175
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
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
In fs/aio.c (ffffffff81325cfa)
Location: fs/aio.c:2175
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
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
In fs/aio.c (ffffffff81332e3a)
Location: fs/aio.c:2175
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
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
In fs/aio.c (ffffffff81345fda)
Location: fs/aio.c:2175
Inline: True
Inline callers:
  - fs/aio.c:__ia32_sys_io_getevents_time32
  - fs/aio.c:__x64_sys_io_getevents_time32
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
