# Function: <code>tomoyo_collect_member</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tomoyo_collect_member(const enum tomoyo_policy_id id, struct list_head *member_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff813704f0)
Location: security/tomoyo/gc.c:473
Inline: False
```
**Symbols:**

```
ffffffff813704f0-ffffffff8137054c: tomoyo_collect_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tomoyo_collect_member(const enum tomoyo_policy_id id, struct list_head *member_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff813a68e0)
Location: security/tomoyo/gc.c:473
Inline: False
```
**Symbols:**

```
ffffffff813a68e0-ffffffff813a6939: tomoyo_collect_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tomoyo_collect_member(const enum tomoyo_policy_id id, struct list_head *member_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff813bd460)
Location: security/tomoyo/gc.c:473
Inline: False
```
**Symbols:**

```
ffffffff813bd460-ffffffff813bd4b9: tomoyo_collect_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tomoyo_collect_member(const enum tomoyo_policy_id id, struct list_head *member_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff813d3d90)
Location: security/tomoyo/gc.c:473
Inline: False
```
**Symbols:**

```
ffffffff813d3d90-ffffffff813d3dd9: tomoyo_collect_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tomoyo_collect_member(const enum tomoyo_policy_id id, struct list_head *member_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff813fa2a0)
Location: security/tomoyo/gc.c:474
Inline: False
```
**Symbols:**

```
ffffffff813fa2a0-ffffffff813fa2e9: tomoyo_collect_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tomoyo_collect_member(const enum tomoyo_policy_id id, struct list_head *member_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff8142b230)
Location: security/tomoyo/gc.c:474
Inline: False
```
**Symbols:**

```
ffffffff8142b230-ffffffff8142b279: tomoyo_collect_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tomoyo_collect_member(const enum tomoyo_policy_id id, struct list_head *member_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff81447b50)
Location: security/tomoyo/gc.c:474
Inline: False
```
**Symbols:**

```
ffffffff81447b50-ffffffff81447b99: tomoyo_collect_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tomoyo_collect_member(const enum tomoyo_policy_id id, struct list_head *member_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff81475760)
Location: security/tomoyo/gc.c:485
Inline: False
```
**Symbols:**

```
ffffffff81475760-ffffffff814757ae: tomoyo_collect_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tomoyo_collect_member(const enum tomoyo_policy_id id, struct list_head *member_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff8148f500)
Location: security/tomoyo/gc.c:485
Inline: False
```
**Symbols:**

```
ffffffff8148f500-ffffffff8148f54e: tomoyo_collect_member (STB_LOCAL)
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
In security/tomoyo/gc.c (ffffffff814e698f)
Location: security/tomoyo/gc.c:485
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
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
In security/tomoyo/gc.c (ffffffff81503d8f)
Location: security/tomoyo/gc.c:485
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
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
In security/tomoyo/gc.c (ffffffff8150a93f)
Location: security/tomoyo/gc.c:485
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
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
In security/tomoyo/gc.c (ffffffff8156803d)
Location: security/tomoyo/gc.c:485
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
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
In security/tomoyo/gc.c (ffffffff81603c23)
Location: security/tomoyo/gc.c:485
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
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
In security/tomoyo/gc.c (ffffffff816b4df3)
Location: security/tomoyo/gc.c:485
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
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
In security/tomoyo/gc.c (ffffffff816ed7cf)
Location: security/tomoyo/gc.c:485
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
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
In security/tomoyo/gc.c (ffffffff8172a59f)
Location: security/tomoyo/gc.c:485
Inline: True
Inline callers:
  - security/tomoyo/gc.c:tomoyo_collect_entry
  - security/tomoyo/gc.c:tomoyo_collect_entry
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
void tomoyo_collect_member(const enum tomoyo_policy_id id, struct list_head *member_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffff800010583210)
Location: security/tomoyo/gc.c:485
Inline: False
```
**Symbols:**

```
ffff800010583210-ffff800010583280: tomoyo_collect_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tomoyo_collect_member(const enum tomoyo_policy_id id, struct list_head *member_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (c07350bc)
Location: security/tomoyo/gc.c:485
Inline: False
```
**Symbols:**

```
c07350bc-c0735124: tomoyo_collect_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tomoyo_collect_member(const enum tomoyo_policy_id id, struct list_head *member_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (c0000000006f1e60)
Location: security/tomoyo/gc.c:485
Inline: False
```
**Symbols:**

```
c0000000006f1e60-c0000000006f1f04: tomoyo_collect_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tomoyo_collect_member(const enum tomoyo_policy_id id, struct list_head *member_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffe0003d355a)
Location: security/tomoyo/gc.c:485
Inline: False
```
**Symbols:**

```
ffffffe0003d355a-ffffffe0003d3636: tomoyo_collect_member (STB_LOCAL)
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
void tomoyo_collect_member(const enum tomoyo_policy_id id, struct list_head *member_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff81487ae0)
Location: security/tomoyo/gc.c:485
Inline: False
```
**Symbols:**

```
ffffffff81487ae0-ffffffff81487b2e: tomoyo_collect_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tomoyo_collect_member(const enum tomoyo_policy_id id, struct list_head *member_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff81478500)
Location: security/tomoyo/gc.c:485
Inline: False
```
**Symbols:**

```
ffffffff81478500-ffffffff8147854e: tomoyo_collect_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tomoyo_collect_member(const enum tomoyo_policy_id id, struct list_head *member_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff81483b80)
Location: security/tomoyo/gc.c:485
Inline: False
```
**Symbols:**

```
ffffffff81483b80-ffffffff81483bce: tomoyo_collect_member (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tomoyo_collect_member(const enum tomoyo_policy_id id, struct list_head *member_list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff8149b6c0)
Location: security/tomoyo/gc.c:485
Inline: False
```
**Symbols:**

```
ffffffff8149b6c0-ffffffff8149b70e: tomoyo_collect_member (STB_LOCAL)
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
