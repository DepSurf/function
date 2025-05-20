# Function: <code>freeze_cgroup</code>

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
In kernel/cgroup_freezer.c (ffffffff81119d17)
Location: kernel/cgroup_freezer.c:318
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_apply_state
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
In kernel/cgroup_freezer.c (ffffffff81121b27)
Location: kernel/cgroup_freezer.c:318
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_apply_state
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
In kernel/cgroup_freezer.c (ffffffff8112a167)
Location: kernel/cgroup_freezer.c:318
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_apply_state
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
In kernel/cgroup/freezer.c (ffffffff8112ae1c)
Location: kernel/cgroup/freezer.c:318
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_apply_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void freeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff81137b70)
Location: kernel/cgroup/freezer.c:318
Inline: False
Direct callers:
  - kernel/cgroup/freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff81137b70-ffffffff81137bce: freeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void freeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff81146480)
Location: kernel/cgroup/freezer.c:318
Inline: False
Direct callers:
  - kernel/cgroup/freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff81146480-ffffffff811464de: freeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void freeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff81152020)
Location: kernel/cgroup/freezer.c:318
Inline: False
Direct callers:
  - kernel/cgroup/freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff81152020-ffffffff8115207e: freeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void freeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff8115e6b0)
Location: kernel/cgroup/legacy_freezer.c:318
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff8115e6b0-ffffffff8115e70e: freeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void freeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a2e0)
Location: kernel/cgroup/legacy_freezer.c:318
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff8116a2e0-ffffffff8116a34a: freeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void freeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff8117be30)
Location: kernel/cgroup/legacy_freezer.c:318
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff8117be30-ffffffff8117be8e: freeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void freeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81178c60)
Location: kernel/cgroup/legacy_freezer.c:318
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff81178c60-ffffffff81178cbe: freeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void freeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff811797d0)
Location: kernel/cgroup/legacy_freezer.c:318
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff811797d0-ffffffff8117982e: freeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void freeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff811a10f0)
Location: kernel/cgroup/legacy_freezer.c:318
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff811a10f0-ffffffff811a114e: freeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void freeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff811d1930)
Location: kernel/cgroup/legacy_freezer.c:318
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff811d1930-ffffffff811d19b6: freeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void freeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81215590)
Location: kernel/cgroup/legacy_freezer.c:311
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff81215590-ffffffff81215616: freeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void freeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff8122aec0)
Location: kernel/cgroup/legacy_freezer.c:316
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff8122aec0-ffffffff8122af46: freeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void freeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81242e80)
Location: kernel/cgroup/legacy_freezer.c:322
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff81242e80-ffffffff81242f06: freeze_cgroup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void freeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffff8000101dde50)
Location: kernel/cgroup/legacy_freezer.c:318
Inline: False
```
**Symbols:**

```
ffff8000101dde50-ffff8000101ddec8: freeze_cgroup (STB_LOCAL)
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
In kernel/cgroup/legacy_freezer.c (c041fc38)
Location: kernel/cgroup/legacy_freezer.c:318
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void freeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (c00000000024bbb0)
Location: kernel/cgroup/legacy_freezer.c:318
Inline: False
```
**Symbols:**

```
c00000000024bbb0-c00000000024bc44: freeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void freeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffe0001555ba)
Location: kernel/cgroup/legacy_freezer.c:318
Inline: False
```
**Symbols:**

```
ffffffe0001555ba-ffffffe00015560e: freeze_cgroup (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void freeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81162900)
Location: kernel/cgroup/legacy_freezer.c:318
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff81162900-ffffffff8116296a: freeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void freeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81155b50)
Location: kernel/cgroup/legacy_freezer.c:318
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff81155b50-ffffffff81155bba: freeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void freeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff811606d0)
Location: kernel/cgroup/legacy_freezer.c:318
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff811606d0-ffffffff8116073a: freeze_cgroup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void freeze_cgroup(struct freezer *freezer);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff8116da40)
Location: kernel/cgroup/legacy_freezer.c:318
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_apply_state
```
**Symbols:**

```
ffffffff8116da40-ffffffff8116daaa: freeze_cgroup (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
