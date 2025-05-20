# Function: <code>irq_work_run_list</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff81170e50)
Location: kernel/irq_work.c:129
Inline: False
Direct callers:
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
```
**Symbols:**

```
ffffffff81170e50-ffffffff81170ebb: irq_work_run_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff8117e540)
Location: kernel/irq_work.c:129
Inline: False
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
ffffffff8117e540-ffffffff8117e5ab: irq_work_run_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff8118a150)
Location: kernel/irq_work.c:129
Inline: False
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
ffffffff8118a150-ffffffff8118a1bb: irq_work_run_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff8118cc60)
Location: kernel/irq_work.c:129
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
ffffffff8118cc60-ffffffff8118cccb: irq_work_run_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff8119a660)
Location: kernel/irq_work.c:132
Inline: False
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
ffffffff8119a660-ffffffff8119a6d5: irq_work_run_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811b00a0)
Location: kernel/irq_work.c:132
Inline: False
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
ffffffff811b00a0-ffffffff811b0115: irq_work_run_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811be6b0)
Location: kernel/irq_work.c:132
Inline: False
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
ffffffff811be6b0-ffffffff811be725: irq_work_run_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811ce250)
Location: kernel/irq_work.c:142
Inline: False
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
ffffffff811ce250-ffffffff811ce2c4: irq_work_run_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811da870)
Location: kernel/irq_work.c:142
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
ffffffff811da870-ffffffff811da8e4: irq_work_run_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811f7540)
Location: kernel/irq_work.c:158
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
ffffffff811f7540-ffffffff811f757e: irq_work_run_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811f60a0)
Location: kernel/irq_work.c:163
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
ffffffff811f60a0-ffffffff811f60de: irq_work_run_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811f6f90)
Location: kernel/irq_work.c:165
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
ffffffff811f6f90-ffffffff811f6fce: irq_work_run_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff81228560)
Location: kernel/irq_work.c:165
Inline: False
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
ffffffff81228560-ffffffff8122859e: irq_work_run_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff81269610)
Location: kernel/irq_work.c:225
Inline: False
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
ffffffff81269610-ffffffff81269655: irq_work_run_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff812be4c0)
Location: kernel/irq_work.c:225
Inline: False
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
ffffffff812be4c0-ffffffff812be511: irq_work_run_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff812e5100)
Location: kernel/irq_work.c:235
Inline: False
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
ffffffff812e5100-ffffffff812e5151: irq_work_run_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff813031b0)
Location: kernel/irq_work.c:235
Inline: False
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
ffffffff813031b0-ffffffff81303201: irq_work_run_list (STB_LOCAL)
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
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffff80001025b008)
Location: kernel/irq_work.c:142
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
ffff80001025b008-ffff80001025b0c4: irq_work_run_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (c048e09c)
Location: kernel/irq_work.c:142
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
c048e09c-c048e15c: irq_work_run_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (c0000000002febf0)
Location: kernel/irq_work.c:142
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
c0000000002febf0-c0000000002fece4: irq_work_run_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffe00019a050)
Location: kernel/irq_work.c:142
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
ffffffe00019a050-ffffffe00019a0c4: irq_work_run_list (STB_LOCAL)
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
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811d2e90)
Location: kernel/irq_work.c:142
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
ffffffff811d2e90-ffffffff811d2f04: irq_work_run_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811c5c60)
Location: kernel/irq_work.c:142
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
ffffffff811c5c60-ffffffff811c5cd0: irq_work_run_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811d0c60)
Location: kernel/irq_work.c:142
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
ffffffff811d0c60-ffffffff811d0cd4: irq_work_run_list (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void irq_work_run_list(struct llist_head *list);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/irq_work.c (ffffffff811def20)
Location: kernel/irq_work.c:142
Inline: True
Direct callers:
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_tick
  - kernel/irq_work.c:irq_work_run
  - kernel/irq_work.c:irq_work_run
```
**Symbols:**

```
ffffffff811def20-ffffffff811def94: irq_work_run_list (STB_LOCAL)
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
