# Function: <code>audit_get_watch</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81129b80)
Location: kernel/audit_watch.c:111
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_update_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
```
**Symbols:**

```
ffffffff81129b80-ffffffff81129b8e: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811325aa)
Location: kernel/audit_watch.c:112
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
```
**Symbols:**

```
ffffffff81131d30-ffffffff81131d3e: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8113c30e)
Location: kernel/audit_watch.c:112
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
```
**Symbols:**

```
ffffffff8113ba90-ffffffff8113ba9e: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8113d9a8)
Location: kernel/audit_watch.c:113
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
```
**Symbols:**

```
ffffffff8113d140-ffffffff8113d14e: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81149f00)
Location: kernel/audit_watch.c:113
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81149f00-ffffffff81149f14: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81158900)
Location: kernel/audit_watch.c:113
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81158900-ffffffff81158914: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811658b0)
Location: kernel/audit_watch.c:113
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff811658b0-ffffffff811658c4: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81172430)
Location: kernel/audit_watch.c:100
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81172430-ffffffff81172444: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8117e2e0)
Location: kernel/audit_watch.c:100
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff8117e2e0-ffffffff8117e2f4: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81191ff2)
Location: kernel/audit_watch.c:100
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_to_parent
  - kernel/audit_watch.c:audit_add_to_parent
  - kernel/audit_watch.c:audit_update_watch
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
```
**Symbols:**

```
ffffffff811915b0-ffffffff811915e7: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8118f182)
Location: kernel/audit_watch.c:100
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_to_parent
  - kernel/audit_watch.c:audit_add_to_parent
  - kernel/audit_watch.c:audit_update_watch
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
```
**Symbols:**

```
ffffffff8118e760-ffffffff8118e797: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff8118ffb3)
Location: kernel/audit_watch.c:100
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
```
**Symbols:**

```
ffffffff8118f6e0-ffffffff8118f717: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811b8e93)
Location: kernel/audit_watch.c:100
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
```
**Symbols:**

```
ffffffff811b85c0-ffffffff811b85f7: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811ebec8)
Location: kernel/audit_watch.c:100
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
```
**Symbols:**

```
ffffffff811eb4b0-ffffffff811eb50b: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81232328)
Location: kernel/audit_watch.c:100
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
```
**Symbols:**

```
ffffffff81231890-ffffffff812318eb: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81248fb8)
Location: kernel/audit_watch.c:100
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
```
**Symbols:**

```
ffffffff81248520-ffffffff8124857b: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81262e48)
Location: kernel/audit_watch.c:100
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
```
**Symbols:**

```
ffffffff81262440-ffffffff8126249b: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffff8000101f39a8)
Location: kernel/audit_watch.c:100
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
```
**Symbols:**

```
ffff8000101f3170-ffff8000101f319c: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (c0433e1c)
Location: kernel/audit_watch.c:100
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
```
**Symbols:**

```
c043366c-c0433688: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (c000000000268608)
Location: kernel/audit_watch.c:100
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
```
**Symbols:**

```
c000000000267bb0-c000000000267bcc: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffe000166d9e)
Location: kernel/audit_watch.c:100
Inline: True
Inline callers:
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
```
**Symbols:**

```
ffffffe0001666ba-ffffffe0001666e0: audit_get_watch (STB_GLOBAL)
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
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81176900)
Location: kernel/audit_watch.c:100
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81176900-ffffffff81176914: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81169aa0)
Location: kernel/audit_watch.c:100
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81169aa0-ffffffff81169ab4: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff811746d0)
Location: kernel/audit_watch.c:100
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff811746d0-ffffffff811746e4: audit_get_watch (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void audit_get_watch(struct audit_watch *watch);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/audit_watch.c (ffffffff81181fb0)
Location: kernel/audit_watch.c:100
Inline: False
Direct callers:
  - kernel/auditfilter.c:audit_dupe_rule
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_add_watch
  - kernel/audit_watch.c:audit_update_watch
```
**Symbols:**

```
ffffffff81181fb0-ffffffff81181fc4: audit_get_watch (STB_GLOBAL)
```
</details>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
