# Function: <code>kobj_ns_ops</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff813eba70)
Location: lib/kobject.c:1008
Inline: True
Inline callers:
  - lib/kobject.c:kobject_namespace
Direct callers:
  - lib/kobject_uevent.c:kobj_bcast_filter
  - lib/kobject_uevent.c:kobj_bcast_filter
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff813ec6d0-ffffffff813ec6f6: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81431e40)
Location: lib/kobject.c:1009
Inline: True
Inline callers:
  - lib/kobject.c:kobject_namespace
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobj_bcast_filter
  - lib/kobject_uevent.c:kobj_bcast_filter
```
**Symbols:**

```
ffffffff81432990-ffffffff814329b6: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8144e0b0)
Location: lib/kobject.c:1009
Inline: True
Inline callers:
  - lib/kobject.c:kobject_namespace
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobj_bcast_filter
  - lib/kobject_uevent.c:kobj_bcast_filter
```
**Symbols:**

```
ffffffff8144ec00-ffffffff8144ec26: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff818ee358)
Location: lib/kobject.c:1012
Inline: True
Inline callers:
  - lib/kobject.c:kobject_namespace
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobj_bcast_filter
  - lib/kobject_uevent.c:kobj_bcast_filter
```
**Symbols:**

```
ffffffff818eee20-ffffffff818eee46: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81974618)
Location: lib/kobject.c:1012
Inline: True
Inline callers:
  - lib/kobject.c:kobject_namespace
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobj_bcast_filter
  - lib/kobject_uevent.c:kobj_bcast_filter
```
**Symbols:**

```
ffffffff819750e0-ffffffff81975109: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff819d0bd0)
Location: lib/kobject.c:1032
Inline: True
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff819d1660-ffffffff819d1689: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0a130)
Location: lib/kobject.c:1032
Inline: True
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81a0abc0-ffffffff81a0abed: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a79a70)
Location: lib/kobject.c:1063
Inline: True
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81a7a580-ffffffff81a7a5ad: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ab0dd0)
Location: lib/kobject.c:1063
Inline: True
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81ab18e0-ffffffff81ab190d: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815eaf60)
Location: lib/kobject.c:1080
Inline: True
Inline callers:
  - lib/kobject.c:kobject_namespace
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff815ebbe0-ffffffff815ebc0d: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8160f880)
Location: lib/kobject.c:1077
Inline: True
Inline callers:
  - lib/kobject.c:kobject_namespace
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff81610500-ffffffff8161052d: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff815f2fc0)
Location: lib/kobject.c:1077
Inline: True
Inline callers:
  - lib/kobject.c:kobject_namespace
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff815f3c40-ffffffff815f3c6d: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81660190)
Location: lib/kobject.c:1077
Inline: True
Inline callers:
  - lib/kobject.c:kobject_namespace
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff81660e10-ffffffff81660e3d: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81779ce0)
Location: lib/kobject.c:1045
Inline: True
Inline callers:
  - lib/kobject.c:kobject_namespace
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff8177a950-ffffffff8177a995: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(const struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff82022d10)
Location: lib/kobject.c:1060
Inline: True
Inline callers:
  - lib/kobject.c:kobject_namespace
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff82023ae0-ffffffff82023b25: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(const struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff820a2d80)
Location: lib/kobject.c:1061
Inline: True
Inline callers:
  - lib/kobject.c:kobject_namespace
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff820a3b50-ffffffff820a3b95: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(const struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff8217ae00)
Location: lib/kobject.c:1069
Inline: True
Inline callers:
  - lib/kobject.c:kobject_namespace
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
  - lib/kobject_uevent.c:kobject_uevent_net_broadcast
```
**Symbols:**

```
ffffffff8217bc30-ffffffff8217bc75: kobj_ns_ops (STB_GLOBAL)
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
const struct kobj_ns_type_operations *kobj_ns_ops(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffff800010d8ad80)
Location: lib/kobject.c:1063
Inline: True
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffff800010d8bb00-ffff800010d8bb38: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c0e854c4)
Location: lib/kobject.c:1063
Inline: True
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
c0e860c4-c0e86104: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (c000000000ecc380)
Location: lib/kobject.c:1063
Inline: True
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
c000000000ecd450-c000000000ecd4b8: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffe0008b42c8)
Location: lib/kobject.c:1063
Inline: True
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffe0008b4cc6-ffffffe0008b4cea: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a4fc20)
Location: lib/kobject.c:1063
Inline: True
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81a50730-ffffffff81a5075d: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81a0cd20)
Location: lib/kobject.c:1063
Inline: True
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81a0d830-ffffffff81a0d85d: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81abc010)
Location: lib/kobject.c:1063
Inline: True
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81abcb20-ffffffff81abcb4d: kobj_ns_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const struct kobj_ns_type_operations *kobj_ns_ops(struct kobject *kobj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/kobject.c (ffffffff81ac8490)
Location: lib/kobject.c:1063
Inline: True
Direct callers:
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
  - lib/kobject_uevent.c:kobject_uevent_env
```
**Symbols:**

```
ffffffff81ac8fa0-ffffffff81ac8fcd: kobj_ns_ops (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct kobject *kobj</code> ➡️ <code>const struct kobject *kobj</code>
</li>
</ul>
</details>
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
