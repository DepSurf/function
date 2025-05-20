# Function: <code>from_mnt_ns</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct ns_common *from_mnt_ns(struct mnt_namespace *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133ddc0)
Location: fs/namespace.c:1794
Inline: False
Direct callers:
  - kernel/nsproxy.c:validate_nsset
```
**Symbols:**

```
ffffffff8133ddc0-ffffffff8133ddcf: from_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct ns_common *from_mnt_ns(struct mnt_namespace *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81349e20)
Location: fs/namespace.c:1800
Inline: False
Direct callers:
  - kernel/nsproxy.c:validate_nsset
```
**Symbols:**

```
ffffffff81349e20-ffffffff81349e2e: from_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct ns_common *from_mnt_ns(struct mnt_namespace *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81350810)
Location: fs/namespace.c:1815
Inline: False
Direct callers:
  - kernel/nsproxy.c:validate_nsset
```
**Symbols:**

```
ffffffff81350810-ffffffff8135081e: from_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct ns_common *from_mnt_ns(struct mnt_namespace *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139ebd0)
Location: fs/namespace.c:1816
Inline: False
Direct callers:
  - kernel/nsproxy.c:validate_nsset
```
**Symbols:**

```
ffffffff8139ebd0-ffffffff8139ebde: from_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct ns_common *from_mnt_ns(struct mnt_namespace *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81421e70)
Location: fs/namespace.c:1857
Inline: False
Direct callers:
  - kernel/nsproxy.c:validate_nsset
```
**Symbols:**

```
ffffffff81421e70-ffffffff81421e84: from_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct ns_common *from_mnt_ns(struct mnt_namespace *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814ae480)
Location: fs/namespace.c:1962
Inline: False
Direct callers:
  - kernel/nsproxy.c:validate_nsset
```
**Symbols:**

```
ffffffff814ae480-ffffffff814ae494: from_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct ns_common *from_mnt_ns(struct mnt_namespace *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e3420)
Location: fs/namespace.c:1949
Inline: False
Direct callers:
  - kernel/nsproxy.c:validate_nsset
```
**Symbols:**

```
ffffffff814e3420-ffffffff814e3434: from_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct ns_common *from_mnt_ns(struct mnt_namespace *mnt);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81517170)
Location: fs/namespace.c:1951
Inline: False
Direct callers:
  - kernel/nsproxy.c:validate_nsset
```
**Symbols:**

```
ffffffff81517170-ffffffff81517184: from_mnt_ns (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
