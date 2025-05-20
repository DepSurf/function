# Function: <code>audit_remove_parent_watches</code>

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
In kernel/audit_watch.c (ffffffff8112a055)
Location: kernel/audit_watch.c:336
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
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
In kernel/audit_watch.c (ffffffff81132214)
Location: kernel/audit_watch.c:337
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
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
In kernel/audit_watch.c (ffffffff8113bf74)
Location: kernel/audit_watch.c:336
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
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
In kernel/audit_watch.c (ffffffff8113d63c)
Location: kernel/audit_watch.c:337
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
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
In kernel/audit_watch.c (ffffffff8114a40c)
Location: kernel/audit_watch.c:337
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
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
In kernel/audit_watch.c (ffffffff81158e3c)
Location: kernel/audit_watch.c:337
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
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
In kernel/audit_watch.c (ffffffff81165ddc)
Location: kernel/audit_watch.c:336
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
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
In kernel/audit_watch.c (ffffffff8117295c)
Location: kernel/audit_watch.c:323
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
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
In kernel/audit_watch.c (ffffffff8117e80c)
Location: kernel/audit_watch.c:323
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void audit_remove_parent_watches(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81191bc0)
Location: kernel/audit_watch.c:321
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
**Symbols:**

```
ffffffff81191bc0-ffffffff81191dff: audit_remove_parent_watches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void audit_remove_parent_watches(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8118ed70)
Location: kernel/audit_watch.c:321
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
**Symbols:**

```
ffffffff8118ed70-ffffffff8118efaf: audit_remove_parent_watches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void audit_remove_parent_watches(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8118fba0)
Location: kernel/audit_watch.c:321
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
**Symbols:**

```
ffffffff8118fba0-ffffffff8118fddf: audit_remove_parent_watches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void audit_remove_parent_watches(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811b8a80)
Location: kernel/audit_watch.c:321
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
**Symbols:**

```
ffffffff811b8a80-ffffffff811b8cbf: audit_remove_parent_watches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void audit_remove_parent_watches(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811eb9c0)
Location: kernel/audit_watch.c:322
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
**Symbols:**

```
ffffffff811eb9c0-ffffffff811ebc1d: audit_remove_parent_watches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void audit_remove_parent_watches(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81231dd0)
Location: kernel/audit_watch.c:322
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
**Symbols:**

```
ffffffff81231dd0-ffffffff8123202d: audit_remove_parent_watches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void audit_remove_parent_watches(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81248a60)
Location: kernel/audit_watch.c:322
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
**Symbols:**

```
ffffffff81248a60-ffffffff81248cbd: audit_remove_parent_watches (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void audit_remove_parent_watches(struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81262940)
Location: kernel/audit_watch.c:322
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_watch_handle_event
```
**Symbols:**

```
ffffffff81262940-ffffffff81262b9d: audit_remove_parent_watches (STB_LOCAL)
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
In kernel/audit_watch.c (ffff8000101f36ac)
Location: kernel/audit_watch.c:323
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
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
In kernel/audit_watch.c (c0433b80)
Location: kernel/audit_watch.c:323
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
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
In kernel/audit_watch.c (c0000000002681ec)
Location: kernel/audit_watch.c:323
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
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
In kernel/audit_watch.c (ffffffe000166b0e)
Location: kernel/audit_watch.c:323
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
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
In kernel/audit_watch.c (ffffffff81176e2c)
Location: kernel/audit_watch.c:323
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
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
In kernel/audit_watch.c (ffffffff81169fcc)
Location: kernel/audit_watch.c:323
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
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
In kernel/audit_watch.c (ffffffff81174bfc)
Location: kernel/audit_watch.c:323
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
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
In kernel/audit_watch.c (ffffffff811824dc)
Location: kernel/audit_watch.c:323
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_watch_handle_event
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
