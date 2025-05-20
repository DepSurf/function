# Function: <code>SyS_futimesat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int SyS_futimesat(long int dfd, long int filename, long int utimes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff812410a0)
Location: fs/utimes.c:203
Inline: True
Inline callers:
  - fs/utimes.c:SyS_utimes
```
**Symbols:**

```
ffffffff812410a0-ffffffff81241173: SyS_futimesat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int SyS_futimesat(long int dfd, long int filename, long int utimes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff812694d5)
Location: fs/utimes.c:204
Inline: True
Inline callers:
  - fs/utimes.c:SyS_utimes
```
**Symbols:**

```
ffffffff812693d0-ffffffff812694a3: SyS_futimesat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int SyS_futimesat(long int dfd, long int filename, long int utimes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff8127c485)
Location: fs/utimes.c:189
Inline: True
Inline callers:
  - fs/utimes.c:SyS_utimes
```
**Symbols:**

```
ffffffff8127c380-ffffffff8127c453: SyS_futimesat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int SyS_futimesat(long int dfd, long int filename, long int utimes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff812897cf)
Location: fs/utimes.c:185
Inline: True
Inline callers:
  - fs/utimes.c:SyS_utimes
```
**Symbols:**

```
ffffffff812896c0-ffffffff8128979b: SyS_futimesat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int SyS_futimesat(long int dfd, long int filename, long int utimes);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/utimes.c (ffffffff812ac30f)
Location: fs/utimes.c:187
Inline: True
Inline callers:
  - fs/utimes.c:SyS_utimes
```
**Symbols:**

```
ffffffff812ac200-ffffffff812ac2db: SyS_futimesat (STB_GLOBAL)
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
