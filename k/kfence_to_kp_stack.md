# Function: <code>kfence_to_kp_stack</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kfence_to_kp_stack(const struct kfence_track *track, void **kp_stack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff813b0470)
Location: mm/kfence/report.c:278
Inline: False
Direct callers:
  - mm/kfence/report.c:__kfence_obj_info
  - mm/kfence/report.c:__kfence_obj_info
```
**Symbols:**

```
ffffffff813b0470-ffffffff813b04f3: kfence_to_kp_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kfence_to_kp_stack(const struct kfence_track *track, void **kp_stack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff81430af0)
Location: mm/kfence/report.c:283
Inline: False
Direct callers:
  - mm/kfence/report.c:__kfence_obj_info
  - mm/kfence/report.c:__kfence_obj_info
```
**Symbols:**

```
ffffffff81430af0-ffffffff81430b73: kfence_to_kp_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kfence_to_kp_stack(const struct kfence_track *track, void **kp_stack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff81466450)
Location: mm/kfence/report.c:283
Inline: False
Direct callers:
  - mm/kfence/report.c:__kfence_obj_info
  - mm/kfence/report.c:__kfence_obj_info
```
**Symbols:**

```
ffffffff81466450-ffffffff81466505: kfence_to_kp_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kfence_to_kp_stack(const struct kfence_track *track, void **kp_stack);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/kfence/report.c (ffffffff81495660)
Location: mm/kfence/report.c:282
Inline: False
Direct callers:
  - mm/kfence/report.c:__kfence_obj_info
  - mm/kfence/report.c:__kfence_obj_info
```
**Symbols:**

```
ffffffff81495660-ffffffff81495715: kfence_to_kp_stack (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
