# Function: <code>seccomp_run_filters</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8113bd02)
Location: kernel/seccomp.c:176
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81143b9b)
Location: kernel/seccomp.c:176
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8114da6b)
Location: kernel/seccomp.c:175
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 seccomp_run_filters(const struct seccomp_data *sd, struct seccomp_filter **match);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8114fe70)
Location: kernel/seccomp.c:184
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8114fe70-ffffffff8114ff26: seccomp_run_filters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 seccomp_run_filters(const struct seccomp_data *sd, struct seccomp_filter **match);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8115c430)
Location: kernel/seccomp.c:186
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8115c430-ffffffff8115c4e9: seccomp_run_filters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 seccomp_run_filters(const struct seccomp_data *sd, struct seccomp_filter **match);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8116ad50)
Location: kernel/seccomp.c:188
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8116ad50-ffffffff8116ae08: seccomp_run_filters (STB_LOCAL)
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
In kernel/seccomp.c (ffffffff81178add)
Location: kernel/seccomp.c:254
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff81185863)
Location: kernel/seccomp.c:254
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff81191793)
Location: kernel/seccomp.c:255
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 seccomp_run_filters(const struct seccomp_data *sd, struct seccomp_filter **match);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a5570)
Location: kernel/seccomp.c:263
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff811a5570-ffffffff811a564e: seccomp_run_filters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 seccomp_run_filters(const struct seccomp_data *sd, struct seccomp_filter **match);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a3890)
Location: kernel/seccomp.c:391
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff811a3890-ffffffff811a39e3: seccomp_run_filters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 seccomp_run_filters(const struct seccomp_data *sd, struct seccomp_filter **match);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a44b0)
Location: kernel/seccomp.c:396
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff811a44b0-ffffffff811a45f8: seccomp_run_filters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 seccomp_run_filters(const struct seccomp_data *sd, struct seccomp_filter **match);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811cdd00)
Location: kernel/seccomp.c:399
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff811cdd00-ffffffff811cde44: seccomp_run_filters (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 seccomp_run_filters(const struct seccomp_data *sd, struct seccomp_filter **match);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81201c20)
Location: kernel/seccomp.c:401
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81201c20-ffffffff81201d73: seccomp_run_filters (STB_LOCAL)
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
In kernel/seccomp.c (ffffffff81249f5c)
Location: kernel/seccomp.c:401
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff8126124c)
Location: kernel/seccomp.c:401
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff8127b44c)
Location: kernel/seccomp.c:406
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffff8000102091d4)
Location: kernel/seccomp.c:255
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (c0447d98)
Location: kernel/seccomp.c:255
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (c0000000002861b8)
Location: kernel/seccomp.c:255
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffe00016b274)
Location: kernel/seccomp.c:255
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff81189db3)
Location: kernel/seccomp.c:255
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff8117cee3)
Location: kernel/seccomp.c:255
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff81187b83)
Location: kernel/seccomp.c:255
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff811954c3)
Location: kernel/seccomp.c:255
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
</ul>
