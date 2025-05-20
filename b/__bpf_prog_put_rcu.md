# Function: <code>__bpf_prog_put_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81180e60)
Location: kernel/bpf/syscall.c:627
Inline: False
```
**Symbols:**

```
ffffffff81180e60-ffffffff81180e9f: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118cee0)
Location: kernel/bpf/syscall.c:690
Inline: False
```
**Symbols:**

```
ffffffff8118cee0-ffffffff8118cf16: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81191c30)
Location: kernel/bpf/syscall.c:767
Inline: False
```
**Symbols:**

```
ffffffff81191c30-ffffffff81191c66: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119f0a0)
Location: kernel/bpf/syscall.c:927
Inline: False
```
**Symbols:**

```
ffffffff8119f0a0-ffffffff8119f0e5: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b5050)
Location: kernel/bpf/syscall.c:1026
Inline: False
```
**Symbols:**

```
ffffffff811b5050-ffffffff811b5095: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c3460)
Location: kernel/bpf/syscall.c:1209
Inline: False
```
**Symbols:**

```
ffffffff811c3460-ffffffff811c34a4: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d41b0)
Location: kernel/bpf/syscall.c:1315
Inline: False
```
**Symbols:**

```
ffffffff811d41b0-ffffffff811d41f4: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e04b0)
Location: kernel/bpf/syscall.c:1328
Inline: False
```
**Symbols:**

```
ffffffff811e04b0-ffffffff811e055b: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fc980)
Location: kernel/bpf/syscall.c:1714
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
**Symbols:**

```
ffffffff811fc980-ffffffff811fc9e5: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fa950)
Location: kernel/bpf/syscall.c:1682
Inline: True
```
**Symbols:**

```
ffffffff811fa950-ffffffff811fa999: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fcaa7)
Location: kernel/bpf/syscall.c:1683
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
```
**Symbols:**

```
ffffffff811fb8a0-ffffffff811fb8e6: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8122e565)
Location: kernel/bpf/syscall.c:1753
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
```
**Symbols:**

```
ffffffff8122cfd0-ffffffff8122d016: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81270b29)
Location: kernel/bpf/syscall.c:1997
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
```
**Symbols:**

```
ffffffff8126f420-ffffffff8126f46f: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c6679)
Location: kernel/bpf/syscall.c:2022
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
```
**Symbols:**

```
ffffffff812c4eb0-ffffffff812c4eff: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812ed989)
Location: kernel/bpf/syscall.c:2100
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
```
**Symbols:**

```
ffffffff812ebfd0-ffffffff812ec01f: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8130c539)
Location: kernel/bpf/syscall.c:2140
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__bpf_prog_put_noref
```
**Symbols:**

```
ffffffff8130a500-ffffffff8130a54f: __bpf_prog_put_rcu (STB_LOCAL)
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
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff800010262be0)
Location: kernel/bpf/syscall.c:1328
Inline: False
```
**Symbols:**

```
ffff800010262be0-ffff800010262cd4: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0495648)
Location: kernel/bpf/syscall.c:1328
Inline: False
```
**Symbols:**

```
c0495648-c04956e8: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0000000003078d0)
Location: kernel/bpf/syscall.c:1328
Inline: False
```
**Symbols:**

```
c0000000003078d0-c0000000003079ec: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019f456)
Location: kernel/bpf/syscall.c:1328
Inline: False
```
**Symbols:**

```
ffffffe00019f456-ffffffe00019f542: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d8ad0)
Location: kernel/bpf/syscall.c:1328
Inline: False
```
**Symbols:**

```
ffffffff811d8ad0-ffffffff811d8b7b: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cb890)
Location: kernel/bpf/syscall.c:1328
Inline: False
```
**Symbols:**

```
ffffffff811cb890-ffffffff811cb93b: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d68a0)
Location: kernel/bpf/syscall.c:1328
Inline: False
```
**Symbols:**

```
ffffffff811d68a0-ffffffff811d694b: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __bpf_prog_put_rcu(struct callback_head *rcu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e4c10)
Location: kernel/bpf/syscall.c:1328
Inline: False
```
**Symbols:**

```
ffffffff811e4c10-ffffffff811e4cbb: __bpf_prog_put_rcu (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
