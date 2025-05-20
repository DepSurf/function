# Function: <code>dump_interrupted</code>

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
In fs/coredump.c (ffffffff8126eea8)
Location: fs/coredump.c:443
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff8129a678)
Location: fs/coredump.c:470
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff812af208)
Location: fs/coredump.c:473
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff812bc638)
Location: fs/coredump.c:475
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff812dff26)
Location: fs/coredump.c:476
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff8130beb6)
Location: fs/coredump.c:476
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff81321716)
Location: fs/coredump.c:476
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff81349002)
Location: fs/coredump.c:502
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff813612a2)
Location: fs/coredump.c:502
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff813a756b)
Location: fs/coredump.c:504
Inline: True
Inline callers:
  - fs/coredump.c:dump_skip
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff813b8dc2)
Location: fs/coredump.c:514
Inline: True
Inline callers:
  - fs/coredump.c:dump_skip
  - fs/coredump.c:dump_skip
  - fs/coredump.c:do_coredump
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool dump_interrupted();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff813bf060)
Location: fs/coredump.c:514
Inline: False
Direct callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff813bf060-ffffffff813bf0a6: dump_interrupted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool dump_interrupted();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8140ee90)
Location: fs/coredump.c:514
Inline: False
Direct callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8140ee90-ffffffff8140eed6: dump_interrupted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool dump_interrupted();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff814845c0)
Location: fs/coredump.c:448
Inline: False
Direct callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff814845c0-ffffffff8148461e: dump_interrupted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool dump_interrupted();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff81517aa0)
Location: fs/coredump.c:454
Inline: False
Direct callers:
  - fs/coredump.c:dump_user_range
  - fs/coredump.c:dump_emit
  - fs/coredump.c:__dump_skip
  - fs/coredump.c:__dump_skip
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff81517aa0-ffffffff81517af5: dump_interrupted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool dump_interrupted();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff8154f390)
Location: fs/coredump.c:456
Inline: False
Direct callers:
  - fs/coredump.c:dump_user_range
  - fs/coredump.c:dump_emit
  - fs/coredump.c:__dump_skip
  - fs/coredump.c:__dump_skip
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff8154f390-ffffffff8154f3e5: dump_interrupted (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool dump_interrupted();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/coredump.c (ffffffff815851d0)
Location: fs/coredump.c:456
Inline: False
Direct callers:
  - fs/coredump.c:dump_user_range
  - fs/coredump.c:dump_emit
  - fs/coredump.c:__dump_skip
  - fs/coredump.c:__dump_skip
  - fs/coredump.c:do_coredump
```
**Symbols:**

```
ffffffff815851d0-ffffffff81585225: dump_interrupted (STB_LOCAL)
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
In fs/coredump.c (ffff800010427874)
Location: fs/coredump.c:502
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (c05f06fc)
Location: fs/coredump.c:502
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (c0000000005375bc)
Location: fs/coredump.c:502
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffe0002c5d84)
Location: fs/coredump.c:502
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff81359882)
Location: fs/coredump.c:502
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff8134a532)
Location: fs/coredump.c:502
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff81357352)
Location: fs/coredump.c:502
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
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
In fs/coredump.c (ffffffff8136aa32)
Location: fs/coredump.c:502
Inline: True
Inline callers:
  - fs/coredump.c:dump_emit
  - fs/coredump.c:do_coredump
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
