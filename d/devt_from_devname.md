# Function: <code>devt_from_devname</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
dev_t devt_from_devname(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81003d60)
Location: init/do_mounts.c:191
Inline: False
```
**Symbols:**

```
ffffffff81003d60-ffffffff81003ef5: devt_from_devname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
dev_t devt_from_devname(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81003c60)
Location: init/do_mounts.c:191
Inline: False
```
**Symbols:**

```
ffffffff81003c60-ffffffff81003df3: devt_from_devname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
dev_t devt_from_devname(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81003c90)
Location: init/do_mounts.c:185
Inline: False
```
**Symbols:**

```
ffffffff81003c90-ffffffff81003e23: devt_from_devname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
dev_t devt_from_devname(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81001940)
Location: init/do_mounts.c:184
Inline: False
```
**Symbols:**

```
ffffffff81001940-ffffffff81001af9: devt_from_devname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
dev_t devt_from_devname(const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002000)
Location: init/do_mounts.c:184
Inline: False
```
**Symbols:**

```
ffffffff81002000-ffffffff810021b9: devt_from_devname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devt_from_devname(const char *name, dev_t *devt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/early-lookup.c (ffffffff836fdf10)
Location: block/early-lookup.c:153
Inline: False
Direct callers:
  - block/early-lookup.c:early_lookup_bdev
```
**Symbols:**

```
ffffffff836fdf10-ffffffff836fe10b: devt_from_devname (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devt_from_devname(const char *name, dev_t *devt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/early-lookup.c (ffffffff839315f0)
Location: block/early-lookup.c:153
Inline: False
Direct callers:
  - block/early-lookup.c:early_lookup_bdev
```
**Symbols:**

```
ffffffff839315f0-ffffffff839317eb: devt_from_devname (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>dev_t *devt</code>
</li>
<li>
<b>Return type changed. </b>
<code>dev_t</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
