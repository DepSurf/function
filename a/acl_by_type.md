# Function: <code>acl_by_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct posix_acl **acl_by_type(struct inode *inode, int type);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (ffffffff8126dda0)
Location: fs/posix_acl.c:24
Inline: True
Inline callers:
  - fs/posix_acl.c:get_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
Direct callers:
  - fs/posix_acl.c:get_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
```
**Symbols:**

```
ffffffff8126dda0-ffffffff8126ddab: acl_by_type.part.2 (STB_LOCAL)
ffffffff8126ddb0-ffffffff8126ddd8: acl_by_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (ffffffff81299826)
Location: fs/posix_acl.c:24
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
Direct callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
```
**Symbols:**

```
ffffffff81299520-ffffffff8129952b: acl_by_type.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (ffffffff812ae346)
Location: fs/posix_acl.c:24
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
Direct callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
```
**Symbols:**

```
ffffffff812ae040-ffffffff812ae04b: acl_by_type.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (ffffffff812bb796)
Location: fs/posix_acl.c:25
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
Direct callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
```
**Symbols:**

```
ffffffff812bc16d-ffffffff812bc178: acl_by_type.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (ffffffff812df086)
Location: fs/posix_acl.c:25
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
Direct callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
```
**Symbols:**

```
ffffffff812dfa6d-ffffffff812dfa78: acl_by_type.part.1 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (ffffffff8130b015)
Location: fs/posix_acl.c:25
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
Direct callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
```
**Symbols:**

```
ffffffff8130ae80-ffffffff8130ae8b: acl_by_type.part.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (ffffffff813208d5)
Location: fs/posix_acl.c:25
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
Direct callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
```
**Symbols:**

```
ffffffff813206c0-ffffffff813206cb: acl_by_type.part.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (ffffffff81348185)
Location: fs/posix_acl.c:26
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
Direct callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
```
**Symbols:**

```
ffffffff81347f80-ffffffff81347f8b: acl_by_type.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (ffffffff81360425)
Location: fs/posix_acl.c:26
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
Direct callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
```
**Symbols:**

```
ffffffff81360220-ffffffff8136022b: acl_by_type.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (ffffffff813a5e95)
Location: fs/posix_acl.c:26
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
Direct callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
```
**Symbols:**

```
ffffffff813a5d20-ffffffff813a5d2b: acl_by_type.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (ffffffff813b6be5)
Location: fs/posix_acl.c:26
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
Direct callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
```
**Symbols:**

```
ffffffff813b6a60-ffffffff813b6a6b: acl_by_type.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (ffffffff813bdc45)
Location: fs/posix_acl.c:26
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
Direct callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
```
**Symbols:**

```
ffffffff813bdac0-ffffffff813bdacb: acl_by_type.part.0 (STB_LOCAL)
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
In fs/posix_acl.c (ffffffff8140da85)
Location: fs/posix_acl.c:27
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/posix_acl.c (ffffffff81482fe5)
Location: fs/posix_acl.c:28
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/posix_acl.c (ffffffff81516265)
Location: fs/posix_acl.c:34
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/posix_acl.c (ffffffff8154dbe5)
Location: fs/posix_acl.c:35
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
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
In fs/posix_acl.c (ffffffff81583a35)
Location: fs/posix_acl.c:35
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (ffff8000104266c4)
Location: fs/posix_acl.c:26
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
Direct callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
```
**Symbols:**

```
ffff800010426478-ffff80001042648c: acl_by_type.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (c05ef2c8)
Location: fs/posix_acl.c:26
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
Direct callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
```
**Symbols:**

```
c05ef08c-c05ef0a4: acl_by_type.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (c000000000535a94)
Location: fs/posix_acl.c:26
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
Direct callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
```
**Symbols:**

```
c000000000535820-c00000000053582c: acl_by_type.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (ffffffe0002c532a)
Location: fs/posix_acl.c:26
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
Direct callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
```
**Symbols:**

```
ffffffe0002c51a2-ffffffe0002c51b6: acl_by_type.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (ffffffff81358a05)
Location: fs/posix_acl.c:26
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
Direct callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
```
**Symbols:**

```
ffffffff81358800-ffffffff8135880b: acl_by_type.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (ffffffff813496b5)
Location: fs/posix_acl.c:26
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
Direct callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
```
**Symbols:**

```
ffffffff813494b0-ffffffff813494bb: acl_by_type.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (ffffffff813564d5)
Location: fs/posix_acl.c:26
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
Direct callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
```
**Symbols:**

```
ffffffff813562d0-ffffffff813562db: acl_by_type.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/posix_acl.c (ffffffff81369bb5)
Location: fs/posix_acl.c:26
Inline: True
Inline callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
Direct callers:
  - fs/posix_acl.c:forget_cached_acl
  - fs/posix_acl.c:set_cached_acl
  - fs/posix_acl.c:get_cached_acl_rcu
  - fs/posix_acl.c:get_cached_acl
```
**Symbols:**

```
ffffffff813699a0-ffffffff813699ab: acl_by_type.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
