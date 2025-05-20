# Function: <code>__ptr_to_hashval</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff815f6a02)
Location: lib/vsprintf.c:765
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_hashval
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
In lib/vsprintf.c (ffffffff8161ba22)
Location: lib/vsprintf.c:768
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_hashval
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
In lib/vsprintf.c (ffffffff815ff2c9)
Location: lib/vsprintf.c:794
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_hashval
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
In lib/vsprintf.c (ffffffff8166d039)
Location: lib/vsprintf.c:795
Inline: True
Inline callers:
  - lib/vsprintf.c:ptr_to_id
  - lib/vsprintf.c:ptr_to_hashval
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int __ptr_to_hashval(const void *ptr, long unsigned int *hashval_out);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (0)
Location: lib/vsprintf.c:761
Inline: False
Direct callers:
  - lib/vsprintf.c:default_pointer
  - lib/vsprintf.c:ptr_to_hashval
```
**Symbols:**

```
ffffffff81783a70-ffffffff81783b56: __ptr_to_hashval (STB_LOCAL)
ffffffff81ea62ee-ffffffff81ea6303: __ptr_to_hashval.cold (STB_LOCAL)
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
In lib/vsprintf.c (ffffffff8204454d)
Location: lib/vsprintf.c:776
Inline: True
Inline callers:
  - lib/vsprintf.c:default_pointer
  - lib/vsprintf.c:ptr_to_hashval
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
In lib/vsprintf.c (ffffffff820c2b4a)
Location: lib/vsprintf.c:776
Inline: True
Inline callers:
  - lib/vsprintf.c:default_pointer
  - lib/vsprintf.c:ptr_to_hashval
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
In lib/vsprintf.c (ffffffff8219d4ca)
Location: lib/vsprintf.c:778
Inline: True
Inline callers:
  - lib/vsprintf.c:default_pointer
  - lib/vsprintf.c:ptr_to_hashval
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
</ul>
