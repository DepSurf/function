# Function: <code>__seccomp_filter_orphan</code>

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
void __seccomp_filter_orphan(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a3700)
Location: kernel/seccomp.c:516
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_filter_release
```
**Symbols:**

```
ffffffff811a3700-ffffffff811a3783: __seccomp_filter_orphan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __seccomp_filter_orphan(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a4320)
Location: kernel/seccomp.c:521
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_filter_release
```
**Symbols:**

```
ffffffff811a4320-ffffffff811a43a3: __seccomp_filter_orphan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __seccomp_filter_orphan(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811cda10)
Location: kernel/seccomp.c:524
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_filter_release
```
**Symbols:**

```
ffffffff811cda10-ffffffff811cda93: __seccomp_filter_orphan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __seccomp_filter_orphan(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff812017b0)
Location: kernel/seccomp.c:526
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_filter_release
```
**Symbols:**

```
ffffffff812017b0-ffffffff8120186f: __seccomp_filter_orphan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __seccomp_filter_orphan(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81249570)
Location: kernel/seccomp.c:526
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_filter_release
```
**Symbols:**

```
ffffffff81249570-ffffffff8124962f: __seccomp_filter_orphan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __seccomp_filter_orphan(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81260960)
Location: kernel/seccomp.c:526
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_filter_release
```
**Symbols:**

```
ffffffff81260960-ffffffff81260a1f: __seccomp_filter_orphan (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __seccomp_filter_orphan(struct seccomp_filter *orig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8127ab30)
Location: kernel/seccomp.c:531
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_attach_filter
  - kernel/seccomp.c:seccomp_filter_release
```
**Symbols:**

```
ffffffff8127ab30-ffffffff8127abef: __seccomp_filter_orphan (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
