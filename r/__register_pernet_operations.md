# Function: <code>__register_pernet_operations</code>

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
In net/core/net_namespace.c (ffffffff8171075c)
Location: net/core/net_namespace.c:771
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
In net/core/net_namespace.c (ffffffff81778099)
Location: net/core/net_namespace.c:771
Inline: True
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
In net/core/net_namespace.c (ffffffff817a51ee)
Location: net/core/net_namespace.c:802
Inline: True
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
In net/core/net_namespace.c (ffffffff817c3462)
Location: net/core/net_namespace.c:868
Inline: True
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
In net/core/net_namespace.c (ffffffff8183cfb2)
Location: net/core/net_namespace.c:870
Inline: True
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
In net/core/net_namespace.c (ffffffff81887862)
Location: net/core/net_namespace.c:927
Inline: True
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
In net/core/net_namespace.c (ffffffff818a80f7)
Location: net/core/net_namespace.c:1041
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In net/core/net_namespace.c (ffffffff818f30f7)
Location: net/core/net_namespace.c:1122
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In net/core/net_namespace.c (ffffffff81925057)
Location: net/core/net_namespace.c:1129
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f95d0)
Location: net/core/net_namespace.c:1127
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_operations
```
**Symbols:**

```
ffffffff819f95d0-ffffffff819f97a9: __register_pernet_operations (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __register_pernet_operations(struct list_head *list, struct pernet_operations *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net_namespace.c (ffffffff819f8e10)
Location: net/core/net_namespace.c:1131
Inline: False
Direct callers:
  - net/core/net_namespace.c:register_pernet_operations
```
**Symbols:**

```
ffffffff819f8e10-ffffffff819f8fe9: __register_pernet_operations (STB_LOCAL)
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
In net/core/net_namespace.c (ffffffff819de047)
Location: net/core/net_namespace.c:1124
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In net/core/net_namespace.c (ffffffff81a8e919)
Location: net/core/net_namespace.c:1134
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In net/core/net_namespace.c (ffffffff81c04839)
Location: net/core/net_namespace.c:1133
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In net/core/net_namespace.c (ffffffff81db3d59)
Location: net/core/net_namespace.c:1153
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In net/core/net_namespace.c (ffffffff81e24409)
Location: net/core/net_namespace.c:1152
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In net/core/net_namespace.c (ffffffff81ee2619)
Location: net/core/net_namespace.c:1201
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In net/core/net_namespace.c (ffff800010bc0b54)
Location: net/core/net_namespace.c:1129
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In net/core/net_namespace.c (c0cdce48)
Location: net/core/net_namespace.c:1129
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In net/core/net_namespace.c (c000000000c9aeb8)
Location: net/core/net_namespace.c:1129
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In net/core/net_namespace.c (ffffffe00074ea2c)
Location: net/core/net_namespace.c:1129
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In net/core/net_namespace.c (ffffffff818c5057)
Location: net/core/net_namespace.c:1129
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In net/core/net_namespace.c (ffffffff8187ef97)
Location: net/core/net_namespace.c:1129
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In net/core/net_namespace.c (ffffffff81916057)
Location: net/core/net_namespace.c:1129
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
In net/core/net_namespace.c (ffffffff81937257)
Location: net/core/net_namespace.c:1129
Inline: True
Inline callers:
  - net/core/net_namespace.c:register_pernet_operations
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
