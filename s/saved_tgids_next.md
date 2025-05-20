# Function: <code>saved_tgids_next</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *saved_tgids_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811605c0)
Location: kernel/trace/trace.c:4731
Inline: False
Direct callers:
  - kernel/trace/trace.c:saved_tgids_start
```
**Symbols:**

```
ffffffff811605c0-ffffffff8116061e: saved_tgids_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *saved_tgids_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8116d680)
Location: kernel/trace/trace.c:4735
Inline: False
Direct callers:
  - kernel/trace/trace.c:saved_tgids_start
```
**Symbols:**

```
ffffffff8116d680-ffffffff8116d6de: saved_tgids_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *saved_tgids_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8117c4b0)
Location: kernel/trace/trace.c:4741
Inline: False
Direct callers:
  - kernel/trace/trace.c:saved_tgids_start
```
**Symbols:**

```
ffffffff8117c4b0-ffffffff8117c509: saved_tgids_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *saved_tgids_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81189cb0)
Location: kernel/trace/trace.c:4764
Inline: False
Direct callers:
  - kernel/trace/trace.c:saved_tgids_start
```
**Symbols:**

```
ffffffff81189cb0-ffffffff81189d09: saved_tgids_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *saved_tgids_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81197540)
Location: kernel/trace/trace.c:4985
Inline: False
Direct callers:
  - kernel/trace/trace.c:saved_tgids_start
```
**Symbols:**

```
ffffffff81197540-ffffffff8119759c: saved_tgids_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *saved_tgids_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a2f00)
Location: kernel/trace/trace.c:5029
Inline: False
Direct callers:
  - kernel/trace/trace.c:saved_tgids_start
```
**Symbols:**

```
ffffffff811a2f00-ffffffff811a2f5c: saved_tgids_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void *saved_tgids_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811bbc93)
Location: kernel/trace/trace.c:5234
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_tgids_start
```
**Symbols:**

```
ffffffff811bbd40-ffffffff811bbda2: saved_tgids_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void *saved_tgids_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b98a3)
Location: kernel/trace/trace.c:5307
Inline: True
Inline callers:
  - kernel/trace/trace.c:saved_tgids_start
```
**Symbols:**

```
ffffffff811b9950-ffffffff811b99b2: saved_tgids_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *saved_tgids_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811b7d90)
Location: kernel/trace/trace.c:5660
Inline: False
```
**Symbols:**

```
ffffffff811b7d90-ffffffff811b7dbe: saved_tgids_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *saved_tgids_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811e2060)
Location: kernel/trace/trace.c:5738
Inline: False
```
**Symbols:**

```
ffffffff811e2060-ffffffff811e208e: saved_tgids_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *saved_tgids_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81218e40)
Location: kernel/trace/trace.c:5750
Inline: False
```
**Symbols:**

```
ffffffff81218e40-ffffffff81218e73: saved_tgids_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *saved_tgids_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81262e60)
Location: kernel/trace/trace.c:5779
Inline: False
```
**Symbols:**

```
ffffffff81262e60-ffffffff81262e93: saved_tgids_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *saved_tgids_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81279e40)
Location: kernel/trace/trace.c:5902
Inline: False
```
**Symbols:**

```
ffffffff81279e40-ffffffff81279e73: saved_tgids_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *saved_tgids_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff81294920)
Location: kernel/trace/trace.c:5921
Inline: False
```
**Symbols:**

```
ffffffff81294920-ffffffff81294953: saved_tgids_next (STB_LOCAL)
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
void *saved_tgids_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffff80001021e168)
Location: kernel/trace/trace.c:5029
Inline: False
Direct callers:
  - kernel/trace/trace.c:saved_tgids_start
```
**Symbols:**

```
ffff80001021e168-ffff80001021e1d0: saved_tgids_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *saved_tgids_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c045be40)
Location: kernel/trace/trace.c:5029
Inline: False
Direct callers:
  - kernel/trace/trace.c:saved_tgids_start
```
**Symbols:**

```
c045be40-c045bedc: saved_tgids_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *saved_tgids_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (c0000000002a0fe0)
Location: kernel/trace/trace.c:5029
Inline: False
Direct callers:
  - kernel/trace/trace.c:saved_tgids_start
```
**Symbols:**

```
c0000000002a0fe0-c0000000002a1078: saved_tgids_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *saved_tgids_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffe00017ac40)
Location: kernel/trace/trace.c:5029
Inline: False
Direct callers:
  - kernel/trace/trace.c:saved_tgids_start
```
**Symbols:**

```
ffffffe00017ac40-ffffffe00017ac90: saved_tgids_next (STB_LOCAL)
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
void *saved_tgids_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8119b520)
Location: kernel/trace/trace.c:5029
Inline: False
Direct callers:
  - kernel/trace/trace.c:saved_tgids_start
```
**Symbols:**

```
ffffffff8119b520-ffffffff8119b57c: saved_tgids_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *saved_tgids_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff8118e5a0)
Location: kernel/trace/trace.c:5029
Inline: False
Direct callers:
  - kernel/trace/trace.c:saved_tgids_start
```
**Symbols:**

```
ffffffff8118e5a0-ffffffff8118e5fc: saved_tgids_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *saved_tgids_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811992f0)
Location: kernel/trace/trace.c:5029
Inline: False
Direct callers:
  - kernel/trace/trace.c:saved_tgids_start
```
**Symbols:**

```
ffffffff811992f0-ffffffff8119934c: saved_tgids_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *saved_tgids_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/trace.c (ffffffff811a6f90)
Location: kernel/trace/trace.c:5029
Inline: False
Direct callers:
  - kernel/trace/trace.c:saved_tgids_start
```
**Symbols:**

```
ffffffff811a6f90-ffffffff811a6fec: saved_tgids_next (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
