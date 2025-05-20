# Function: <code>audit_add_to_parent</code>

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
In kernel/audit_watch.c (ffffffff8112a39a)
Location: kernel/audit_watch.c:379
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
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
In kernel/audit_watch.c (ffffffff81132559)
Location: kernel/audit_watch.c:380
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
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
In kernel/audit_watch.c (ffffffff8113c2b9)
Location: kernel/audit_watch.c:379
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
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
In kernel/audit_watch.c (ffffffff8113d94f)
Location: kernel/audit_watch.c:380
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
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
In kernel/audit_watch.c (ffffffff8114a722)
Location: kernel/audit_watch.c:380
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
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
In kernel/audit_watch.c (ffffffff811591a4)
Location: kernel/audit_watch.c:380
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
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
In kernel/audit_watch.c (ffffffff81166144)
Location: kernel/audit_watch.c:379
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
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
In kernel/audit_watch.c (ffffffff81172c6a)
Location: kernel/audit_watch.c:366
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
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
In kernel/audit_watch.c (ffffffff8117eb18)
Location: kernel/audit_watch.c:366
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void audit_add_to_parent(struct audit_krule *krule, struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81191660)
Location: kernel/audit_watch.c:364
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
```
**Symbols:**

```
ffffffff81191660-ffffffff811917a9: audit_add_to_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void audit_add_to_parent(struct audit_krule *krule, struct audit_parent *parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8118e810)
Location: kernel/audit_watch.c:364
Inline: False
Direct callers:
  - kernel/audit_watch.c:audit_add_watch
```
**Symbols:**

```
ffffffff8118e810-ffffffff8118e959: audit_add_to_parent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8119005e)
Location: kernel/audit_watch.c:364
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811b8f3e)
Location: kernel/audit_watch.c:364
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811ebf6f)
Location: kernel/audit_watch.c:365
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
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
In kernel/audit_watch.c (ffffffff812323cf)
Location: kernel/audit_watch.c:365
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
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
In kernel/audit_watch.c (ffffffff8124905f)
Location: kernel/audit_watch.c:365
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
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
In kernel/audit_watch.c (ffffffff81262eef)
Location: kernel/audit_watch.c:365
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
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
In kernel/audit_watch.c (ffff8000101f3a2c)
Location: kernel/audit_watch.c:366
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
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
In kernel/audit_watch.c (c0433ea8)
Location: kernel/audit_watch.c:366
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
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
In kernel/audit_watch.c (c0000000002686bc)
Location: kernel/audit_watch.c:366
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
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
In kernel/audit_watch.c (ffffffe000166e2e)
Location: kernel/audit_watch.c:366
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
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
In kernel/audit_watch.c (ffffffff81177138)
Location: kernel/audit_watch.c:366
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
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
In kernel/audit_watch.c (ffffffff8116a2d8)
Location: kernel/audit_watch.c:366
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
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
In kernel/audit_watch.c (ffffffff81174f08)
Location: kernel/audit_watch.c:366
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
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
In kernel/audit_watch.c (ffffffff811827e8)
Location: kernel/audit_watch.c:366
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
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
</ul>
