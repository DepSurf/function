# Function: <code>freezer_change_state</code>

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
In kernel/cgroup_freezer.c (ffffffff8111a16a)
Location: kernel/cgroup_freezer.c:385
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_write
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
In kernel/cgroup_freezer.c (ffffffff81121f87)
Location: kernel/cgroup_freezer.c:385
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_write
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
In kernel/cgroup_freezer.c (ffffffff8112a5b7)
Location: kernel/cgroup_freezer.c:385
Inline: True
Inline callers:
  - kernel/cgroup_freezer.c:freezer_write
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
In kernel/cgroup/freezer.c (ffffffff8112b2d7)
Location: kernel/cgroup/freezer.c:385
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
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
In kernel/cgroup/freezer.c (ffffffff811380d7)
Location: kernel/cgroup/freezer.c:385
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
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
In kernel/cgroup/freezer.c (ffffffff811468c6)
Location: kernel/cgroup/freezer.c:385
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
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
In kernel/cgroup/freezer.c (ffffffff81152596)
Location: kernel/cgroup/freezer.c:385
Inline: True
Inline callers:
  - kernel/cgroup/freezer.c:freezer_write
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
In kernel/cgroup/legacy_freezer.c (ffffffff8115ebf1)
Location: kernel/cgroup/legacy_freezer.c:385
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
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
In kernel/cgroup/legacy_freezer.c (ffffffff8116a851)
Location: kernel/cgroup/legacy_freezer.c:385
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void freezer_change_state(struct freezer *freezer, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff8117c2f0)
Location: kernel/cgroup/legacy_freezer.c:385
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
**Symbols:**

```
ffffffff8117c2f0-ffffffff8117c40b: freezer_change_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void freezer_change_state(struct freezer *freezer, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81179160)
Location: kernel/cgroup/legacy_freezer.c:385
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
**Symbols:**

```
ffffffff81179160-ffffffff811792ad: freezer_change_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void freezer_change_state(struct freezer *freezer, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81179cd0)
Location: kernel/cgroup/legacy_freezer.c:385
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
**Symbols:**

```
ffffffff81179cd0-ffffffff81179e1d: freezer_change_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void freezer_change_state(struct freezer *freezer, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff811a15f0)
Location: kernel/cgroup/legacy_freezer.c:385
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
**Symbols:**

```
ffffffff811a15f0-ffffffff811a173d: freezer_change_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void freezer_change_state(struct freezer *freezer, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff811d1f30)
Location: kernel/cgroup/legacy_freezer.c:385
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
**Symbols:**

```
ffffffff811d1f30-ffffffff811d2080: freezer_change_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void freezer_change_state(struct freezer *freezer, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81215c60)
Location: kernel/cgroup/legacy_freezer.c:378
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
**Symbols:**

```
ffffffff81215c60-ffffffff81215db0: freezer_change_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void freezer_change_state(struct freezer *freezer, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff8122b590)
Location: kernel/cgroup/legacy_freezer.c:383
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
**Symbols:**

```
ffffffff8122b590-ffffffff8122b6e9: freezer_change_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void freezer_change_state(struct freezer *freezer, bool freeze);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81243580)
Location: kernel/cgroup/legacy_freezer.c:389
Inline: False
Direct callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
```
**Symbols:**

```
ffffffff81243580-ffffffff812436d9: freezer_change_state (STB_LOCAL)
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
In kernel/cgroup/legacy_freezer.c (ffff8000101de700)
Location: kernel/cgroup/legacy_freezer.c:385
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
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
In kernel/cgroup/legacy_freezer.c (c04201b8)
Location: kernel/cgroup/legacy_freezer.c:385
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
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
In kernel/cgroup/legacy_freezer.c (c00000000024c5cc)
Location: kernel/cgroup/legacy_freezer.c:385
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
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
In kernel/cgroup/legacy_freezer.c (ffffffe000155b56)
Location: kernel/cgroup/legacy_freezer.c:385
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
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
In kernel/cgroup/legacy_freezer.c (ffffffff81162e71)
Location: kernel/cgroup/legacy_freezer.c:385
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
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
In kernel/cgroup/legacy_freezer.c (ffffffff811560c1)
Location: kernel/cgroup/legacy_freezer.c:385
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
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
In kernel/cgroup/legacy_freezer.c (ffffffff81160c41)
Location: kernel/cgroup/legacy_freezer.c:385
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
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
In kernel/cgroup/legacy_freezer.c (ffffffff8116e023)
Location: kernel/cgroup/legacy_freezer.c:385
Inline: True
Inline callers:
  - kernel/cgroup/legacy_freezer.c:freezer_write
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
