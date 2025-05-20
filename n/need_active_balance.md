# Function: <code>need_active_balance</code>

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
In kernel/sched/fair.c (ffffffff810bd832)
Location: kernel/sched/fair.c:6894
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810c0fbe)
Location: kernel/sched/fair.c:7360
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810c6faa)
Location: kernel/sched/fair.c:7936
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810c0baa)
Location: kernel/sched/fair.c:7933
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810c8374)
Location: kernel/sched/fair.c:8386
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810d02ae)
Location: kernel/sched/fair.c:8739
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810d9ad4)
Location: kernel/sched/fair.c:8830
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810e0d53)
Location: kernel/sched/fair.c:8768
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810eb3e3)
Location: kernel/sched/fair.c:8751
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810f5228)
Location: kernel/sched/fair.c:9437
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810f32db)
Location: kernel/sched/fair.c:9538
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int need_active_balance(struct lb_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff810f3010)
Location: kernel/sched/fair.c:9585
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff810f3010-ffffffff810f3159: need_active_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int need_active_balance(struct lb_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8110c3e0)
Location: kernel/sched/fair.c:9826
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff8110c3e0-ffffffff8110c582: need_active_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int need_active_balance(struct lb_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff81127dd0)
Location: kernel/sched/fair.c:9909
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff81127dd0-ffffffff81127fa8: need_active_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int need_active_balance(struct lb_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811511e0)
Location: kernel/sched/fair.c:10430
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff811511e0-ffffffff811513b8: need_active_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int need_active_balance(struct lb_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff811615c0)
Location: kernel/sched/fair.c:10730
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff811615c0-ffffffff811617ca: need_active_balance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int need_active_balance(struct lb_env *env);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/fair.c (ffffffff8116b920)
Location: kernel/sched/fair.c:11163
Inline: False
Direct callers:
  - kernel/sched/fair.c:load_balance
  - kernel/sched/fair.c:load_balance
```
**Symbols:**

```
ffffffff8116b920-ffffffff8116bb1b: need_active_balance (STB_LOCAL)
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
In kernel/sched/fair.c (ffff80001014b5a4)
Location: kernel/sched/fair.c:8751
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (c039922c)
Location: kernel/sched/fair.c:8751
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (c00000000019db78)
Location: kernel/sched/fair.c:8751
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffe0000f4dca)
Location: kernel/sched/fair.c:8751
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810e5543)
Location: kernel/sched/fair.c:8751
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810d46ed)
Location: kernel/sched/fair.c:8751
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810e1913)
Location: kernel/sched/fair.c:8751
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
In kernel/sched/fair.c (ffffffff810ed4d2)
Location: kernel/sched/fair.c:8751
Inline: True
Inline callers:
  - kernel/sched/fair.c:load_balance
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
