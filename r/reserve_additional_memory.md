# Function: <code>reserve_additional_memory</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
enum bp_state reserve_additional_memory();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff814c68c0)
Location: drivers/xen/balloon.c:287
Inline: False
Direct callers:
  - drivers/xen/balloon.c:balloon_process
  - drivers/xen/balloon.c:alloc_xenballooned_pages
```
**Symbols:**

```
ffffffff814c68c0-ffffffff814c6a34: reserve_additional_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
enum bp_state reserve_additional_memory();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81517090)
Location: drivers/xen/balloon.c:300
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81517090-ffffffff81517260: reserve_additional_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
enum bp_state reserve_additional_memory();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81543470)
Location: drivers/xen/balloon.c:297
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81543470-ffffffff81543640: reserve_additional_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
enum bp_state reserve_additional_memory();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81557300)
Location: drivers/xen/balloon.c:298
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81557300-ffffffff815574c8: reserve_additional_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
enum bp_state reserve_additional_memory();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff815bb330)
Location: drivers/xen/balloon.c:343
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff815bb330-ffffffff815bb605: reserve_additional_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
enum bp_state reserve_additional_memory();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/balloon.c (0)
Location: drivers/xen/balloon.c:343
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff815f39d0-ffffffff815f3bde: reserve_additional_memory (STB_LOCAL)
ffffffff815f4200-ffffffff815f42c3: reserve_additional_memory.cold.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
enum bp_state reserve_additional_memory();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/balloon.c (0)
Location: drivers/xen/balloon.c:292
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff8160e9d0-ffffffff8160eb38: reserve_additional_memory (STB_LOCAL)
ffffffff8160f0b0-ffffffff8160f12b: reserve_additional_memory.cold.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
enum bp_state reserve_additional_memory();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/balloon.c (0)
Location: drivers/xen/balloon.c:289
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff816427e0-ffffffff8164294c: reserve_additional_memory (STB_LOCAL)
ffffffff81642ea4-ffffffff81642f22: reserve_additional_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
enum bp_state reserve_additional_memory();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/balloon.c (0)
Location: drivers/xen/balloon.c:287
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81664d90-ffffffff81664efc: reserve_additional_memory (STB_LOCAL)
ffffffff81665451-ffffffff816654cf: reserve_additional_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
enum bp_state reserve_additional_memory();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/balloon.c (0)
Location: drivers/xen/balloon.c:286
Inline: False
Direct callers:
  - drivers/xen/balloon.c:add_ballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff817141c0-ffffffff817142ba: reserve_additional_memory (STB_LOCAL)
ffffffff81714c11-ffffffff81714c49: reserve_additional_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
enum bp_state reserve_additional_memory();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/balloon.c (0)
Location: drivers/xen/balloon.c:271
Inline: False
Direct callers:
  - drivers/xen/balloon.c:add_ballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff817310a0-ffffffff817311f7: reserve_additional_memory (STB_LOCAL)
ffffffff81c04c81-ffffffff81c04cd8: reserve_additional_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
enum bp_state reserve_additional_memory();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/balloon.c (0)
Location: drivers/xen/balloon.c:271
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81714a20-ffffffff81714b77: reserve_additional_memory (STB_LOCAL)
ffffffff81bf690b-ffffffff81bf6962: reserve_additional_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
enum bp_state reserve_additional_memory();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/balloon.c (0)
Location: drivers/xen/balloon.c:276
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff817918e0-ffffffff81791a37: reserve_additional_memory (STB_LOCAL)
ffffffff81cf5527-ffffffff81cf557e: reserve_additional_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
enum bp_state reserve_additional_memory();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/balloon.c (0)
Location: drivers/xen/balloon.c:278
Inline: False
Direct callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff818c9d00-ffffffff818c9e70: reserve_additional_memory (STB_LOCAL)
ffffffff81ebd62c-ffffffff81ebd676: reserve_additional_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
enum bp_state reserve_additional_memory();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81a1afb0)
Location: drivers/xen/balloon.c:278
Inline: False
Direct callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff81a1afb0-ffffffff81a1b181: reserve_additional_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
enum bp_state reserve_additional_memory();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81a64160)
Location: drivers/xen/balloon.c:260
Inline: False
Direct callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff81a64160-ffffffff81a64331: reserve_additional_memory (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
enum bp_state reserve_additional_memory();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffffffff81ab69a0)
Location: drivers/xen/balloon.c:259
Inline: False
Direct callers:
  - drivers/xen/balloon.c:xen_alloc_ballooned_pages
  - drivers/xen/balloon.c:balloon_thread
```
**Symbols:**

```
ffffffff81ab69a0-ffffffff81ab6ba0: reserve_additional_memory (STB_LOCAL)
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
enum bp_state reserve_additional_memory();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/balloon.c (ffff80001082eb90)
Location: drivers/xen/balloon.c:287
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffff80001082eb90-ffff80001082ed20: reserve_additional_memory (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
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
In drivers/xen/balloon.c (ffffffff8162af55)
Location: drivers/xen/balloon.c:396
Inline: True
Inline callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
enum bp_state reserve_additional_memory();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/balloon.c (0)
Location: drivers/xen/balloon.c:287
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff81658bd0-ffffffff81658d3c: reserve_additional_memory (STB_LOCAL)
ffffffff81659291-ffffffff8165930f: reserve_additional_memory.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
enum bp_state reserve_additional_memory();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/balloon.c (0)
Location: drivers/xen/balloon.c:287
Inline: False
Direct callers:
  - drivers/xen/balloon.c:alloc_xenballooned_pages
  - drivers/xen/balloon.c:balloon_process
```
**Symbols:**

```
ffffffff816731e0-ffffffff8167334c: reserve_additional_memory (STB_LOCAL)
ffffffff8167388c-ffffffff8167390a: reserve_additional_memory.cold (STB_LOCAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
