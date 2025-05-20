# Function: <code>clk_enable_unlock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e52d0)
Location: drivers/clk/clk.c:137
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_enable
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_unregister
```
**Symbols:**

```
ffffffff816e52d0-ffffffff816e537e: clk_enable_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8174a4e0)
Location: drivers/clk/clk.c:137
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_disable_lock
```
**Symbols:**

```
ffffffff8174a4e0-ffffffff8174a58e: clk_enable_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81532d60)
Location: drivers/clk/clk.c:137
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_disable_lock
```
**Symbols:**

```
ffffffff81532d60-ffffffff81532e0e: clk_enable_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81545c60)
Location: drivers/clk/clk.c:137
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_disable_lock
```
**Symbols:**

```
ffffffff81545c60-ffffffff81545cc1: clk_enable_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815a7bd0)
Location: drivers/clk/clk.c:159
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_disable_lock
```
**Symbols:**

```
ffffffff815a7bd0-ffffffff815a7c32: clk_enable_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815df020)
Location: drivers/clk/clk.c:169
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_disable_lock
```
**Symbols:**

```
ffffffff815df020-ffffffff815df080: clk_enable_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815f8950)
Location: drivers/clk/clk.c:167
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_disable_lock
```
**Symbols:**

```
ffffffff815f8950-ffffffff815f89b0: clk_enable_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162b6d0)
Location: drivers/clk/clk.c:177
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_disable_lock
```
**Symbols:**

```
ffffffff8162b6d0-ffffffff8162b730: clk_enable_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8164e2d0)
Location: drivers/clk/clk.c:183
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_disable_lock
```
**Symbols:**

```
ffffffff8164e2d0-ffffffff8164e330: clk_enable_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fbfc0)
Location: drivers/clk/clk.c:187
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable
```
**Symbols:**

```
ffffffff816fbfc0-ffffffff816fc020: clk_enable_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81718ec0)
Location: drivers/clk/clk.c:187
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable
```
**Symbols:**

```
ffffffff81718ec0-ffffffff81718f20: clk_enable_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fa1c0)
Location: drivers/clk/clk.c:187
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable
```
**Symbols:**

```
ffffffff816fa1c0-ffffffff816fa220: clk_enable_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff817751b0)
Location: drivers/clk/clk.c:187
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable
```
**Symbols:**

```
ffffffff817751b0-ffffffff81775210: clk_enable_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818aaea0)
Location: drivers/clk/clk.c:180
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable
```
**Symbols:**

```
ffffffff818aaea0-ffffffff818aaf1c: clk_enable_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819f64d0)
Location: drivers/clk/clk.c:180
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable
```
**Symbols:**

```
ffffffff819f64d0-ffffffff819f654c: clk_enable_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a3ec60)
Location: drivers/clk/clk.c:180
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable
```
**Symbols:**

```
ffffffff81a3ec60-ffffffff81a3ecdc: clk_enable_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8a590)
Location: drivers/clk/clk.c:180
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_disable
```
**Symbols:**

```
ffffffff81a8a590-ffffffff81a8a60c: clk_enable_unlock (STB_LOCAL)
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
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107bf3e0)
Location: drivers/clk/clk.c:183
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_disable_lock
```
**Symbols:**

```
ffff8000107bf3e0-ffff8000107bf45c: clk_enable_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08e83a4)
Location: drivers/clk/clk.c:183
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_disable_lock
```
**Symbols:**

```
c08e83a4-c08e848c: clk_enable_unlock (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050cd4a)
Location: drivers/clk/clk.c:183
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_disable_lock
```
**Symbols:**

```
ffffffe00050cd4a-ffffffe00050cdb8: clk_enable_unlock (STB_LOCAL)
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
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81614330)
Location: drivers/clk/clk.c:183
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_disable_lock
```
**Symbols:**

```
ffffffff81614330-ffffffff81614390: clk_enable_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81608860)
Location: drivers/clk/clk.c:183
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_disable_lock
```
**Symbols:**

```
ffffffff81608860-ffffffff816088c0: clk_enable_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81642110)
Location: drivers/clk/clk.c:183
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_disable_lock
```
**Symbols:**

```
ffffffff81642110-ffffffff81642170: clk_enable_unlock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void clk_enable_unlock(long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165c4f0)
Location: drivers/clk/clk.c:183
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:__clk_set_parent_before
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_core_enable_lock
  - drivers/clk/clk.c:clk_core_disable_lock
```
**Symbols:**

```
ffffffff8165c4f0-ffffffff8165c550: clk_enable_unlock (STB_LOCAL)
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
