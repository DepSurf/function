# Function: <code>prealloc_init</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81195271)
Location: kernel/bpf/hashtab.c:123
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8119c3f0)
Location: kernel/bpf/hashtab.c:133
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811abcf0)
Location: kernel/bpf/hashtab.c:138
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811c316d)
Location: kernel/bpf/hashtab.c:138
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811d4be4)
Location: kernel/bpf/hashtab.c:142
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811e79a6)
Location: kernel/bpf/hashtab.c:134
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f4106)
Location: kernel/bpf/hashtab.c:134
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int prealloc_init(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812174a0)
Location: kernel/bpf/hashtab.c:249
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff812174a0-ffffffff81217656: prealloc_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int prealloc_init(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812195a0)
Location: kernel/bpf/hashtab.c:276
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff812195a0-ffffffff81219763: prealloc_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int prealloc_init(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8121cfa0)
Location: kernel/bpf/hashtab.c:276
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff8121cfa0-ffffffff8121d160: prealloc_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int prealloc_init(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81253f20)
Location: kernel/bpf/hashtab.c:306
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff81253f20-ffffffff812540d7: prealloc_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int prealloc_init(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8129c4c0)
Location: kernel/bpf/hashtab.c:322
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff8129c4c0-ffffffff8129c685: prealloc_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int prealloc_init(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff812f89b0)
Location: kernel/bpf/hashtab.c:302
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff812f89b0-ffffffff812f8b75: prealloc_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int prealloc_init(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff81326b40)
Location: kernel/bpf/hashtab.c:313
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff81326b40-ffffffff81326d05: prealloc_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int prealloc_init(struct bpf_htab *htab);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff8134b190)
Location: kernel/bpf/hashtab.c:318
Inline: False
Direct callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
**Symbols:**

```
ffffffff8134b190-ffffffff8134b355: prealloc_init (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffff800010277a48)
Location: kernel/bpf/hashtab.c:134
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c04aa948)
Location: kernel/bpf/hashtab.c:134
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (c000000000320c20)
Location: kernel/bpf/hashtab.c:134
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffe0001b0526)
Location: kernel/bpf/hashtab.c:134
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ec726)
Location: kernel/bpf/hashtab.c:134
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811df4b6)
Location: kernel/bpf/hashtab.c:134
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811ea4f6)
Location: kernel/bpf/hashtab.c:134
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/hashtab.c (ffffffff811f88d6)
Location: kernel/bpf/hashtab.c:134
Inline: True
Inline callers:
  - kernel/bpf/hashtab.c:htab_map_alloc
```
</details>
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
