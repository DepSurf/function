# Function: <code>percpu_counter_sync</code>

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
void percpu_counter_sync(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff815f9c20)
Location: lib/percpu_counter.c:107
Inline: False
Direct callers:
  - mm/util.c:sync_overcommit_as
```
**Symbols:**

```
ffffffff815f9c20-ffffffff815f9c54: percpu_counter_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void percpu_counter_sync(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff815dc800)
Location: lib/percpu_counter.c:107
Inline: False
Direct callers:
  - mm/util.c:sync_overcommit_as
```
**Symbols:**

```
ffffffff815dc800-ffffffff815dc834: percpu_counter_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void percpu_counter_sync(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff81648140)
Location: lib/percpu_counter.c:107
Inline: False
Direct callers:
  - mm/util.c:sync_overcommit_as
```
**Symbols:**

```
ffffffff81648140-ffffffff81648174: percpu_counter_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void percpu_counter_sync(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8175e580)
Location: lib/percpu_counter.c:107
Inline: False
Direct callers:
  - mm/util.c:sync_overcommit_as
```
**Symbols:**

```
ffffffff8175e580-ffffffff8175e5bf: percpu_counter_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void percpu_counter_sync(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8188bae0)
Location: lib/percpu_counter.c:107
Inline: False
Direct callers:
  - mm/util.c:sync_overcommit_as
```
**Symbols:**

```
ffffffff8188bae0-ffffffff8188bb1f: percpu_counter_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void percpu_counter_sync(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff818ce070)
Location: lib/percpu_counter.c:112
Inline: False
Direct callers:
  - mm/util.c:sync_overcommit_as
```
**Symbols:**

```
ffffffff818ce070-ffffffff818ce0af: percpu_counter_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void percpu_counter_sync(struct percpu_counter *fbc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/percpu_counter.c (ffffffff8191fad0)
Location: lib/percpu_counter.c:112
Inline: False
Direct callers:
  - mm/util.c:sync_overcommit_as
```
**Symbols:**

```
ffffffff8191fad0-ffffffff8191fb0f: percpu_counter_sync (STB_GLOBAL)
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
