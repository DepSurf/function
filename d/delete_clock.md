# Function: <code>delete_clock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void delete_clock(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff810f9db0)
Location: kernel/time/posix-clock.c:224
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_release
  - kernel/time/posix-clock.c:posix_clock_unregister
```
**Symbols:**

```
ffffffff810f9db0-ffffffff810f9dce: delete_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void delete_clock(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff81101050)
Location: kernel/time/posix-clock.c:224
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - kernel/time/posix-clock.c:posix_clock_release
```
**Symbols:**

```
ffffffff81101050-ffffffff8110106e: delete_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void delete_clock(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff81108d10)
Location: kernel/time/posix-clock.c:224
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - kernel/time/posix-clock.c:posix_clock_release
```
**Symbols:**

```
ffffffff81108d10-ffffffff81108d2e: delete_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void delete_clock(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff8110aed0)
Location: kernel/time/posix-clock.c:192
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - kernel/time/posix-clock.c:posix_clock_release
```
**Symbols:**

```
ffffffff8110aed0-ffffffff8110aeef: delete_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void delete_clock(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff81116080)
Location: kernel/time/posix-clock.c:192
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - kernel/time/posix-clock.c:posix_clock_release
```
**Symbols:**

```
ffffffff81116080-ffffffff811160a2: delete_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void delete_clock(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff81122930)
Location: kernel/time/posix-clock.c:192
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - kernel/time/posix-clock.c:posix_clock_release
```
**Symbols:**

```
ffffffff81122930-ffffffff81122951: delete_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void delete_clock(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff8112e010)
Location: kernel/time/posix-clock.c:179
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - kernel/time/posix-clock.c:posix_clock_release
```
**Symbols:**

```
ffffffff8112e010-ffffffff8112e031: delete_clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void delete_clock(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/posix-clock.c (ffffffff81138a20)
Location: kernel/time/posix-clock.c:179
Inline: False
Direct callers:
  - kernel/time/posix-clock.c:posix_clock_unregister
  - kernel/time/posix-clock.c:posix_clock_release
```
**Symbols:**

```
ffffffff81138a20-ffffffff81138a41: delete_clock (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
