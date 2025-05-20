# Function: <code>handle_path</code>

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
In kernel/auditsc.c (ffffffff81128b2a)
Location: kernel/auditsc.c:1613
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff81130cbe)
Location: kernel/auditsc.c:1612
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff8113aa2e)
Location: kernel/auditsc.c:1617
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff8113c069)
Location: kernel/auditsc.c:1626
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff81148de9)
Location: kernel/auditsc.c:1626
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff811577bc)
Location: kernel/auditsc.c:1633
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff811647bc)
Location: kernel/auditsc.c:1621
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff811714eb)
Location: kernel/auditsc.c:1764
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff8117d36b)
Location: kernel/auditsc.c:1764
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void handle_path(const struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1795
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff8118efd0-ffffffff8118f125: handle_path (STB_LOCAL)
ffffffff81191501-ffffffff8119153c: handle_path.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void handle_path(const struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/auditsc.c (0)
Location: kernel/auditsc.c:1813
Inline: False
Direct callers:
  - kernel/auditsc.c:__audit_inode
```
**Symbols:**

```
ffffffff8118c240-ffffffff8118c391: handle_path (STB_LOCAL)
ffffffff81be4988-ffffffff81be49c3: handle_path.cold (STB_LOCAL)
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
In kernel/auditsc.c (ffffffff8118e73b)
Location: kernel/auditsc.c:1810
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff811b754b)
Location: kernel/auditsc.c:1821
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff811ea2a8)
Location: kernel/auditsc.c:2112
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff81230488)
Location: kernel/auditsc.c:2090
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff81246fab)
Location: kernel/auditsc.c:2087
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff81260e22)
Location: kernel/auditsc.c:2082
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffff8000101f21a0)
Location: kernel/auditsc.c:1764
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (c0432744)
Location: kernel/auditsc.c:1764
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (c000000000266904)
Location: kernel/auditsc.c:1764
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffe000165942)
Location: kernel/auditsc.c:1764
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff8117598b)
Location: kernel/auditsc.c:1764
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff81168b2b)
Location: kernel/auditsc.c:1764
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff8117375b)
Location: kernel/auditsc.c:1764
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
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
In kernel/auditsc.c (ffffffff81180f95)
Location: kernel/auditsc.c:1764
Inline: True
Inline callers:
  - kernel/auditsc.c:__audit_inode
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
