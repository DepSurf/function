# Function: <code>bsg_kref_release_function</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bsg_kref_release_function(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff813d54a0)
Location: block/bsg.c:697
Inline: False
Direct callers:
  - block/bsg.c:bsg_unregister_queue
  - block/bsg.c:bsg_open
  - block/bsg.c:bsg_release
```
**Symbols:**

```
ffffffff813d54a0-ffffffff813d54c7: bsg_kref_release_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bsg_kref_release_function(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff8141b160)
Location: block/bsg.c:697
Inline: False
Direct callers:
  - block/bsg.c:bsg_unregister_queue
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
```
**Symbols:**

```
ffffffff8141b160-ffffffff8141b187: bsg_kref_release_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bsg_kref_release_function(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff814366a0)
Location: block/bsg.c:700
Inline: False
Direct callers:
  - block/bsg.c:bsg_unregister_queue
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
```
**Symbols:**

```
ffffffff814366a0-ffffffff814366c7: bsg_kref_release_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bsg_kref_release_function(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff81443ee0)
Location: block/bsg.c:694
Inline: False
Direct callers:
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
```
**Symbols:**

```
ffffffff81443ee0-ffffffff81443f07: bsg_kref_release_function (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bsg_kref_release_function(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg.c (ffffffff81470970)
Location: block/bsg.c:692
Inline: False
Direct callers:
  - block/bsg.c:bsg_release
  - block/bsg.c:bsg_open
```
**Symbols:**

```
ffffffff81470970-ffffffff8147099a: bsg_kref_release_function (STB_LOCAL)
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
