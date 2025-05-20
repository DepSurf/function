# Function: <code>__fprop_add_percpu</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __fprop_add_percpu(struct fprop_global *p, struct fprop_local_percpu *pl, long int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/flex_proportions.c (ffffffff81777bf0)
Location: lib/flex_proportions.c:220
Inline: False
Direct callers:
  - lib/flex_proportions.c:__fprop_add_percpu_max
```
**Symbols:**

```
ffffffff81777bf0-ffffffff81777c4c: __fprop_add_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __fprop_add_percpu(struct fprop_global *p, struct fprop_local_percpu *pl, long int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/flex_proportions.c (ffffffff820208c0)
Location: lib/flex_proportions.c:216
Inline: False
Direct callers:
  - lib/flex_proportions.c:__fprop_add_percpu_max
```
**Symbols:**

```
ffffffff820208c0-ffffffff8202091c: __fprop_add_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __fprop_add_percpu(struct fprop_global *p, struct fprop_local_percpu *pl, long int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/flex_proportions.c (ffffffff820a0900)
Location: lib/flex_proportions.c:216
Inline: False
Direct callers:
  - lib/flex_proportions.c:__fprop_add_percpu_max
```
**Symbols:**

```
ffffffff820a0900-ffffffff820a095c: __fprop_add_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __fprop_add_percpu(struct fprop_global *p, struct fprop_local_percpu *pl, long int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/flex_proportions.c (ffffffff821788e0)
Location: lib/flex_proportions.c:216
Inline: False
Direct callers:
  - lib/flex_proportions.c:__fprop_add_percpu_max
```
**Symbols:**

```
ffffffff821788e0-ffffffff8217893c: __fprop_add_percpu (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
