# Function: <code>kgdb_reenter_check</code>

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
In kernel/debug/debug_core.c (ffffffff81130335)
Location: kernel/debug/debug_core.c:414
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
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
In kernel/debug/debug_core.c (ffffffff81138645)
Location: kernel/debug/debug_core.c:414
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
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
In kernel/debug/debug_core.c (ffffffff811423d5)
Location: kernel/debug/debug_core.c:414
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
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
In kernel/debug/debug_core.c (ffffffff81143c18)
Location: kernel/debug/debug_core.c:415
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
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
In kernel/debug/debug_core.c (ffffffff811508cb)
Location: kernel/debug/debug_core.c:415
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
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
In kernel/debug/debug_core.c (ffffffff8115f499)
Location: kernel/debug/debug_core.c:415
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
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
In kernel/debug/debug_core.c (ffffffff8116c1db)
Location: kernel/debug/debug_core.c:472
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
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
In kernel/debug/debug_core.c (ffffffff81178fe8)
Location: kernel/debug/debug_core.c:472
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
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
In kernel/debug/debug_core.c (ffffffff81184e38)
Location: kernel/debug/debug_core.c:472
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int kgdb_reenter_check(struct kgdb_state *ks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:513
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
ffffffff81198ec0-ffffffff81198f93: kgdb_reenter_check (STB_LOCAL)
ffffffff81199497-ffffffff811994c6: kgdb_reenter_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_reenter_check(struct kgdb_state *ks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8119647a)
Location: kernel/debug/debug_core.c:530
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
ffffffff81196300-ffffffff811963b7: kgdb_reenter_check.part.0 (STB_LOCAL)
ffffffff81be4bbe-ffffffff81be4bec: kgdb_reenter_check.part.0.cold (STB_LOCAL)
ffffffff811963c0-ffffffff811963e4: kgdb_reenter_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_reenter_check(struct kgdb_state *ks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811972fe)
Location: kernel/debug/debug_core.c:529
Inline: True
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
ffffffff811972d0-ffffffff811973a3: kgdb_reenter_check (STB_LOCAL)
ffffffff81bd6a31-ffffffff81bd6a60: kgdb_reenter_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int kgdb_reenter_check(struct kgdb_state *ks);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff811c0ecd)
Location: kernel/debug/debug_core.c:526
Inline: True
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
ffffffff811c0ea0-ffffffff811c0fec: kgdb_reenter_check (STB_LOCAL)
ffffffff81cb3a4c-ffffffff81cb3a7b: kgdb_reenter_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int kgdb_reenter_check(struct kgdb_state *ks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/debug/debug_core.c (0)
Location: kernel/debug/debug_core.c:527
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
ffffffff811f4450-ffffffff811f459f: kgdb_reenter_check (STB_LOCAL)
ffffffff81e648bb-ffffffff81e648e7: kgdb_reenter_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kgdb_reenter_check(struct kgdb_state *ks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8123b320)
Location: kernel/debug/debug_core.c:515
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
ffffffff8123b320-ffffffff8123b4ab: kgdb_reenter_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kgdb_reenter_check(struct kgdb_state *ks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff81252330)
Location: kernel/debug/debug_core.c:515
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
ffffffff81252330-ffffffff812524bb: kgdb_reenter_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kgdb_reenter_check(struct kgdb_state *ks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/debug/debug_core.c (ffffffff8126c180)
Location: kernel/debug/debug_core.c:515
Inline: False
Direct callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
**Symbols:**

```
ffffffff8126c180-ffffffff8126c30b: kgdb_reenter_check (STB_LOCAL)
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
In kernel/debug/debug_core.c (ffff8000101fa9bc)
Location: kernel/debug/debug_core.c:472
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
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
In kernel/debug/debug_core.c (c043aab8)
Location: kernel/debug/debug_core.c:472
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
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
In kernel/debug/debug_core.c (c000000000272488)
Location: kernel/debug/debug_core.c:472
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In kernel/debug/debug_core.c (ffffffff8117d458)
Location: kernel/debug/debug_core.c:472
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
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
In kernel/debug/debug_core.c (ffffffff811705a8)
Location: kernel/debug/debug_core.c:472
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
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
In kernel/debug/debug_core.c (ffffffff8117b228)
Location: kernel/debug/debug_core.c:472
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
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
In kernel/debug/debug_core.c (ffffffff81188b48)
Location: kernel/debug/debug_core.c:472
Inline: True
Inline callers:
  - kernel/debug/debug_core.c:kgdb_handle_exception
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
