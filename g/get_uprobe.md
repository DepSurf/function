# Function: <code>get_uprobe</code>

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
In kernel/events/uprobes.c (ffffffff81186f7b)
Location: kernel/events/uprobes.c:361
Inline: True
Inline callers:
  - kernel/events/uprobes.c:__find_uprobe
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_notify_resume
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
In kernel/events/uprobes.c (ffffffff8119bca6)
Location: kernel/events/uprobes.c:363
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:__find_uprobe
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
In kernel/events/uprobes.c (ffffffff811ab698)
Location: kernel/events/uprobes.c:364
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:__find_uprobe
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
In kernel/events/uprobes.c (ffffffff811b2b10)
Location: kernel/events/uprobes.c:372
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:__find_uprobe
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
In kernel/events/uprobes.c (ffffffff811c675c)
Location: kernel/events/uprobes.c:372
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:__find_uprobe
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
In kernel/events/uprobes.c (ffffffff811e6871)
Location: kernel/events/uprobes.c:372
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:__find_uprobe
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
In kernel/events/uprobes.c (ffffffff811f73cd)
Location: kernel/events/uprobes.c:561
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:__find_uprobe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct uprobe *get_uprobe(struct uprobe *uprobe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8120c5b0)
Location: kernel/events/uprobes.c:549
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handler_chain
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:__find_uprobe
```
**Symbols:**

```
ffffffff8120c5b0-ffffffff8120c5c8: get_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct uprobe *get_uprobe(struct uprobe *uprobe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812198a0)
Location: kernel/events/uprobes.c:601
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:__find_uprobe
```
**Symbols:**

```
ffffffff812198a0-ffffffff812198b8: get_uprobe (STB_LOCAL)
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
In kernel/events/uprobes.c (ffffffff81248ae5)
Location: kernel/events/uprobes.c:595
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:dup_utask
  - kernel/events/uprobes.c:build_probe_list
  - kernel/events/uprobes.c:build_probe_list
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:__find_uprobe
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
In kernel/events/uprobes.c (ffffffff812531f5)
Location: kernel/events/uprobes.c:595
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:dup_utask
  - kernel/events/uprobes.c:build_probe_list
  - kernel/events/uprobes.c:build_probe_list
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:__find_uprobe
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
In kernel/events/uprobes.c (ffffffff812573e5)
Location: kernel/events/uprobes.c:595
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:find_uprobe
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
In kernel/events/uprobes.c (ffffffff81293175)
Location: kernel/events/uprobes.c:596
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:find_uprobe
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
In kernel/events/uprobes.c (ffffffff812e8c04)
Location: kernel/events/uprobes.c:590
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:__find_uprobe
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
In kernel/events/uprobes.c (ffffffff81352994)
Location: kernel/events/uprobes.c:593
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:__find_uprobe
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
In kernel/events/uprobes.c (ffffffff81383ba4)
Location: kernel/events/uprobes.c:590
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:__find_uprobe
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
In kernel/events/uprobes.c (ffffffff813ad01d)
Location: kernel/events/uprobes.c:590
Inline: True
Inline callers:
  - kernel/events/uprobes.c:prepare_uretprobe
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:alloc_uprobe
  - kernel/events/uprobes.c:__find_uprobe
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
In kernel/events/uprobes.c (ffff8000102a7e08)
Location: kernel/events/uprobes.c:601
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handler_chain
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:__find_uprobe
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
In kernel/events/uprobes.c (c04d72c0)
Location: kernel/events/uprobes.c:601
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:__find_uprobe
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
In kernel/events/uprobes.c (c00000000035b8cc)
Location: kernel/events/uprobes.c:601
Inline: True
Inline callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:__find_uprobe
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
<summary>In <code>aws</code>: ✅</summary>

```c
struct uprobe *get_uprobe(struct uprobe *uprobe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81211ef0)
Location: kernel/events/uprobes.c:601
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:__find_uprobe
```
**Symbols:**

```
ffffffff81211ef0-ffffffff81211f08: get_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct uprobe *get_uprobe(struct uprobe *uprobe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81204c80)
Location: kernel/events/uprobes.c:601
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:__find_uprobe
```
**Symbols:**

```
ffffffff81204c80-ffffffff81204c98: get_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct uprobe *get_uprobe(struct uprobe *uprobe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8120fc90)
Location: kernel/events/uprobes.c:601
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:__find_uprobe
```
**Symbols:**

```
ffffffff8120fc90-ffffffff8120fca8: get_uprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct uprobe *get_uprobe(struct uprobe *uprobe);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8121eba0)
Location: kernel/events/uprobes.c:601
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
  - kernel/events/uprobes.c:uprobe_copy_process
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:uprobe_mmap
  - kernel/events/uprobes.c:__find_uprobe
```
**Symbols:**

```
ffffffff8121eba0-ffffffff8121ebb8: get_uprobe (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
