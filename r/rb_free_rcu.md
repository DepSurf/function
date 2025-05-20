# Function: <code>rb_free_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate ⚠️</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Static Duplication

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81179190)
Location: kernel/events/internal.h:60
Inline: False
```
```
In kernel/events/ring_buffer.c (ffffffff81185f40)
Location: kernel/events/internal.h:60
Inline: False
```
**Symbols:**

```
ffffffff81179190-ffffffff8117919f: rb_free_rcu (STB_LOCAL)
ffffffff81185f40-ffffffff81185f4f: rb_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81189aa0)
Location: kernel/events/internal.h:60
Inline: False
```
**Symbols:**

```
ffffffff81189aa0-ffffffff81189aaf: rb_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81198e70)
Location: kernel/events/internal.h:60
Inline: False
```
**Symbols:**

```
ffffffff81198e70-ffffffff81198e7f: rb_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811a0f50)
Location: kernel/events/internal.h:60
Inline: False
```
**Symbols:**

```
ffffffff811a0f50-ffffffff811a0f5f: rb_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811b4850)
Location: kernel/events/internal.h:61
Inline: False
```
**Symbols:**

```
ffffffff811b4850-ffffffff811b485f: rb_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811d39d0)
Location: kernel/events/internal.h:61
Inline: False
```
**Symbols:**

```
ffffffff811d39d0-ffffffff811d39df: rb_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811e3da0)
Location: kernel/events/internal.h:61
Inline: False
```
**Symbols:**

```
ffffffff811e3da0-ffffffff811e3daf: rb_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811faf70)
Location: kernel/events/internal.h:62
Inline: False
```
**Symbols:**

```
ffffffff811faf70-ffffffff811faf7f: rb_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81208040)
Location: kernel/events/internal.h:62
Inline: False
```
**Symbols:**

```
ffffffff81208040-ffffffff8120804f: rb_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81230cb0)
Location: kernel/events/internal.h:63
Inline: False
```
**Symbols:**

```
ffffffff81230cb0-ffffffff81230cbf: rb_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123a8c0)
Location: kernel/events/internal.h:63
Inline: False
```
**Symbols:**

```
ffffffff8123a8c0-ffffffff8123a8cf: rb_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8123f130)
Location: kernel/events/internal.h:63
Inline: False
```
**Symbols:**

```
ffffffff8123f130-ffffffff8123f13f: rb_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81279a80)
Location: kernel/events/internal.h:63
Inline: False
```
**Symbols:**

```
ffffffff81279a80-ffffffff81279a8f: rb_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff812ccca0)
Location: kernel/events/internal.h:63
Inline: False
```
**Symbols:**

```
ffffffff812ccca0-ffffffff812cccb5: rb_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81334de0)
Location: kernel/events/internal.h:63
Inline: False
```
**Symbols:**

```
ffffffff81334de0-ffffffff81334df5: rb_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81365b20)
Location: kernel/events/internal.h:63
Inline: False
```
**Symbols:**

```
ffffffff81365b20-ffffffff81365b35: rb_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8138ec40)
Location: kernel/events/internal.h:63
Inline: False
```
**Symbols:**

```
ffffffff8138ec40-ffffffff8138ec55: rb_free_rcu (STB_LOCAL)
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
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffff8000102916b8)
Location: kernel/events/internal.h:62
Inline: False
```
**Symbols:**

```
ffff8000102916b8-ffff8000102916d0: rb_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c04c26dc)
Location: kernel/events/internal.h:62
Inline: False
```
**Symbols:**

```
c04c26dc-c04c26f4: rb_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (c00000000033fb80)
Location: kernel/events/internal.h:62
Inline: False
```
**Symbols:**

```
c00000000033fb80-c00000000033fbb0: rb_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffe0001c4148)
Location: kernel/events/internal.h:62
Inline: False
```
**Symbols:**

```
ffffffe0001c4148-ffffffe0001c4162: rb_free_rcu (STB_LOCAL)
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
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff81200660)
Location: kernel/events/internal.h:62
Inline: False
```
**Symbols:**

```
ffffffff81200660-ffffffff8120066f: rb_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811f33b0)
Location: kernel/events/internal.h:62
Inline: False
```
**Symbols:**

```
ffffffff811f33b0-ffffffff811f33bf: rb_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff811fe430)
Location: kernel/events/internal.h:62
Inline: False
```
**Symbols:**

```
ffffffff811fe430-ffffffff811fe43f: rb_free_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rb_free_rcu(struct callback_head *callback_head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/core.c (ffffffff8120d490)
Location: kernel/events/internal.h:62
Inline: False
```
**Symbols:**

```
ffffffff8120d490-ffffffff8120d49f: rb_free_rcu (STB_LOCAL)
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
