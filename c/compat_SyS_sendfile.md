# Function: <code>compat_SyS_sendfile</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int compat_SyS_sendfile(long int out_fd, long int in_fd, long int offset, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff8120df20)
Location: fs/read_write.c:1316
Inline: False
```
**Symbols:**

```
ffffffff8120df20-ffffffff8120dfb4: compat_SyS_sendfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int compat_SyS_sendfile(long int out_fd, long int in_fd, long int offset, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81234790)
Location: fs/read_write.c:1461
Inline: False
```
**Symbols:**

```
ffffffff81234790-ffffffff81234827: compat_SyS_sendfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int compat_SyS_sendfile(long int out_fd, long int in_fd, long int offset, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81247340)
Location: fs/read_write.c:1490
Inline: False
```
**Symbols:**

```
ffffffff81247340-ffffffff812473d7: compat_SyS_sendfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int compat_SyS_sendfile(long int out_fd, long int in_fd, long int offset, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81252b40)
Location: fs/read_write.c:1501
Inline: False
```
**Symbols:**

```
ffffffff81252b40-ffffffff81252bd7: compat_SyS_sendfile (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int compat_SyS_sendfile(long int out_fd, long int in_fd, long int offset, long int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/read_write.c (ffffffff81274c40)
Location: fs/read_write.c:1504
Inline: False
```
**Symbols:**

```
ffffffff81274c40-ffffffff81274cd7: compat_SyS_sendfile (STB_GLOBAL)
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
