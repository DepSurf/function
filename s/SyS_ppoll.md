# Function: <code>SyS_ppoll</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int SyS_ppoll(long int ufds, long int nfds, long int tsp, long int sigmask, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81222570)
Location: fs/select.c:991
Inline: False
```
**Symbols:**

```
ffffffff81222570-ffffffff81222711: SyS_ppoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int SyS_ppoll(long int ufds, long int nfds, long int tsp, long int sigmask, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8124a230)
Location: fs/select.c:997
Inline: False
```
**Symbols:**

```
ffffffff8124a230-ffffffff8124a3d1: SyS_ppoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int SyS_ppoll(long int ufds, long int nfds, long int tsp, long int sigmask, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8125d1f0)
Location: fs/select.c:1005
Inline: False
```
**Symbols:**

```
ffffffff8125d1f0-ffffffff8125d384: SyS_ppoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int SyS_ppoll(long int ufds, long int nfds, long int tsp, long int sigmask, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8126a4c0)
Location: fs/select.c:1049
Inline: False
```
**Symbols:**

```
ffffffff8126a4c0-ffffffff8126a64d: SyS_ppoll (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int SyS_ppoll(long int ufds, long int nfds, long int tsp, long int sigmask, long int sigsetsize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8128cd60)
Location: fs/select.c:1046
Inline: False
```
**Symbols:**

```
ffffffff8128cd60-ffffffff8128cee7: SyS_ppoll (STB_GLOBAL)
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
