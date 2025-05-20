# Function: <code>tomoyo_collect_acl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void tomoyo_collect_acl(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff81370490)
Location: security/tomoyo/gc.c:493
Inline: False
```
**Symbols:**

```
ffffffff81370490-ffffffff813704e7: tomoyo_collect_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void tomoyo_collect_acl(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff813a6880)
Location: security/tomoyo/gc.c:493
Inline: False
```
**Symbols:**

```
ffffffff813a6880-ffffffff813a68d4: tomoyo_collect_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void tomoyo_collect_acl(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff813bd400)
Location: security/tomoyo/gc.c:493
Inline: False
```
**Symbols:**

```
ffffffff813bd400-ffffffff813bd454: tomoyo_collect_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tomoyo_collect_acl(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff813d3d40)
Location: security/tomoyo/gc.c:493
Inline: False
```
**Symbols:**

```
ffffffff813d3d40-ffffffff813d3d84: tomoyo_collect_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tomoyo_collect_acl(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff813fa250)
Location: security/tomoyo/gc.c:494
Inline: False
```
**Symbols:**

```
ffffffff813fa250-ffffffff813fa294: tomoyo_collect_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tomoyo_collect_acl(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff8142b1e0)
Location: security/tomoyo/gc.c:494
Inline: False
```
**Symbols:**

```
ffffffff8142b1e0-ffffffff8142b224: tomoyo_collect_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tomoyo_collect_acl(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff81447b00)
Location: security/tomoyo/gc.c:494
Inline: False
```
**Symbols:**

```
ffffffff81447b00-ffffffff81447b44: tomoyo_collect_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tomoyo_collect_acl(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff81475710)
Location: security/tomoyo/gc.c:506
Inline: False
```
**Symbols:**

```
ffffffff81475710-ffffffff81475759: tomoyo_collect_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tomoyo_collect_acl(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff8148f4b0)
Location: security/tomoyo/gc.c:506
Inline: False
```
**Symbols:**

```
ffffffff8148f4b0-ffffffff8148f4f9: tomoyo_collect_acl (STB_LOCAL)
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
In security/tomoyo/gc.c (ffffffff814e67b0)
Location: security/tomoyo/gc.c:506
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
In security/tomoyo/gc.c (ffffffff81503bb0)
Location: security/tomoyo/gc.c:506
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
In security/tomoyo/gc.c (ffffffff8150a760)
Location: security/tomoyo/gc.c:506
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
In security/tomoyo/gc.c (ffffffff81567e23)
Location: security/tomoyo/gc.c:506
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
In security/tomoyo/gc.c (ffffffff81603a23)
Location: security/tomoyo/gc.c:506
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
In security/tomoyo/gc.c (ffffffff816b4bf3)
Location: security/tomoyo/gc.c:506
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
In security/tomoyo/gc.c (ffffffff816ed5d3)
Location: security/tomoyo/gc.c:506
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
In security/tomoyo/gc.c (ffffffff8172a3a3)
Location: security/tomoyo/gc.c:506
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
void tomoyo_collect_acl(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffff8000105831a0)
Location: security/tomoyo/gc.c:506
Inline: False
```
**Symbols:**

```
ffff8000105831a0-ffff800010583210: tomoyo_collect_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tomoyo_collect_acl(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (c0735058)
Location: security/tomoyo/gc.c:506
Inline: False
```
**Symbols:**

```
c0735058-c07350bc: tomoyo_collect_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tomoyo_collect_acl(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (c0000000006f1dc0)
Location: security/tomoyo/gc.c:506
Inline: False
```
**Symbols:**

```
c0000000006f1dc0-c0000000006f1e60: tomoyo_collect_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tomoyo_collect_acl(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffe0003d3486)
Location: security/tomoyo/gc.c:506
Inline: False
```
**Symbols:**

```
ffffffe0003d3486-ffffffe0003d355a: tomoyo_collect_acl (STB_LOCAL)
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
void tomoyo_collect_acl(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff81487a90)
Location: security/tomoyo/gc.c:506
Inline: False
```
**Symbols:**

```
ffffffff81487a90-ffffffff81487ad9: tomoyo_collect_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tomoyo_collect_acl(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff814784b0)
Location: security/tomoyo/gc.c:506
Inline: False
```
**Symbols:**

```
ffffffff814784b0-ffffffff814784f9: tomoyo_collect_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tomoyo_collect_acl(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff81483b30)
Location: security/tomoyo/gc.c:506
Inline: False
```
**Symbols:**

```
ffffffff81483b30-ffffffff81483b79: tomoyo_collect_acl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tomoyo_collect_acl(struct list_head *list);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/gc.c (ffffffff8149b670)
Location: security/tomoyo/gc.c:506
Inline: False
```
**Symbols:**

```
ffffffff8149b670-ffffffff8149b6b9: tomoyo_collect_acl (STB_LOCAL)
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
