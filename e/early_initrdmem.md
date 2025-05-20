# Function: <code>early_initrdmem</code>

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
int early_initrdmem(char *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts_initrd.c (ffffffff82cc403e)
Location: init/do_mounts_initrd.c:31
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrd
```
**Symbols:**

```
ffffffff82cc403e-ffffffff82cc40a3: early_initrdmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int early_initrdmem(char *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts_initrd.c (ffffffff82fb0168)
Location: init/do_mounts_initrd.c:31
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrd
```
**Symbols:**

```
ffffffff82fb0168-ffffffff82fb01cd: early_initrdmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int early_initrdmem(char *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts_initrd.c (ffffffff831ba1cb)
Location: init/do_mounts_initrd.c:31
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrd
```
**Symbols:**

```
ffffffff831ba1cb-ffffffff831ba230: early_initrdmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int early_initrdmem(char *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts_initrd.c (ffffffff8329a689)
Location: init/do_mounts_initrd.c:31
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrd
```
**Symbols:**

```
ffffffff8329a689-ffffffff8329a6ee: early_initrdmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int early_initrdmem(char *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts_initrd.c (ffffffff8344897d)
Location: init/do_mounts_initrd.c:51
Inline: False
Direct callers:
  - init/do_mounts_initrd.c:early_initrd
```
**Symbols:**

```
ffffffff8344897d-ffffffff834489f8: early_initrdmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int early_initrdmem(char *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts_initrd.c (ffffffff83e62911)
Location: init/do_mounts_initrd.c:51
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:early_initrd
```
**Symbols:**

```
ffffffff83e62860-ffffffff83e628d9: early_initrdmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int early_initrdmem(char *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts_initrd.c (ffffffff83682ec1)
Location: init/do_mounts_initrd.c:51
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:early_initrd
```
**Symbols:**

```
ffffffff83682e10-ffffffff83682e89: early_initrdmem (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int early_initrdmem(char *p);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/do_mounts_initrd.c (ffffffff838b1fa1)
Location: init/do_mounts_initrd.c:51
Inline: True
Inline callers:
  - init/do_mounts_initrd.c:early_initrd
```
**Symbols:**

```
ffffffff838b1ef0-ffffffff838b1f69: early_initrdmem (STB_LOCAL)
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
