# Function: <code>rfkill_set_block</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81811900)
Location: net/rfkill/core.c:268
Inline: False
Direct callers:
  - net/rfkill/core.c:__rfkill_switch_all
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:rfkill_resume
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_epo
```
**Symbols:**

```
ffffffff81811900-ffffffff81811a2c: rfkill_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81884770)
Location: net/rfkill/core.c:247
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
ffffffff81884770-ffffffff8188489c: rfkill_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff818b8fe0)
Location: net/rfkill/core.c:247
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
ffffffff818b8fe0-ffffffff818b910c: rfkill_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff818df980)
Location: net/rfkill/core.c:304
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
ffffffff818df980-ffffffff818dfad5: rfkill_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81965690)
Location: net/rfkill/core.c:304
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
ffffffff81965690-ffffffff819657ee: rfkill_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff819bef10)
Location: net/rfkill/core.c:318
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
ffffffff819bef10-ffffffff819bf05b: rfkill_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff819f62a0)
Location: net/rfkill/core.c:320
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
ffffffff819f62a0-ffffffff819f63eb: rfkill_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81a65330)
Location: net/rfkill/core.c:308
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
ffffffff81a65330-ffffffff81a6547b: rfkill_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81a9be90)
Location: net/rfkill/core.c:308
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
ffffffff81a9be90-ffffffff81a9bfdb: rfkill_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81b97d10)
Location: net/rfkill/core.c:308
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
ffffffff81b97d10-ffffffff81b97e76: rfkill_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81ba7a10)
Location: net/rfkill/core.c:310
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
ffffffff81ba7a10-ffffffff81ba7b79: rfkill_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81b96ba0)
Location: net/rfkill/core.c:311
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
ffffffff81b96ba0-ffffffff81b96d0a: rfkill_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/rfkill/core.c (0)
Location: net/rfkill/core.c:311
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:rfkill_resume
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
ffffffff81c63180-ffffffff81c632d6: rfkill_set_block (STB_LOCAL)
ffffffff81d41cbe-ffffffff81d41cd2: rfkill_set_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/rfkill/core.c (0)
Location: net/rfkill/core.c:311
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:rfkill_resume
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
ffffffff81e05b30-ffffffff81e05ca4: rfkill_set_block (STB_LOCAL)
ffffffff81f0e5f2-ffffffff81f0e607: rfkill_set_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/rfkill/core.c (0)
Location: net/rfkill/core.c:311
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:rfkill_resume
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
ffffffff81fdade0-ffffffff81fdaf54: rfkill_set_block (STB_LOCAL)
ffffffff820b55af-ffffffff820b55c4: rfkill_set_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/rfkill/core.c (0)
Location: net/rfkill/core.c:311
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:rfkill_resume
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
ffffffff82056ad0-ffffffff82056c44: rfkill_set_block (STB_LOCAL)
ffffffff82136b38-ffffffff82136b4d: rfkill_set_block.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/rfkill/core.c (0)
Location: net/rfkill/core.c:312
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_open
  - net/rfkill/core.c:rfkill_resume
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
ffffffff82129190-ffffffff82129304: rfkill_set_block (STB_LOCAL)
ffffffff82218924-ffffffff82218939: rfkill_set_block.cold (STB_LOCAL)
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
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffff800010d6c610)
Location: net/rfkill/core.c:308
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
ffff800010d6c610-ffff800010d6c810: rfkill_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (c0e6a22c)
Location: net/rfkill/core.c:308
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
c0e6a22c-c0e6a368: rfkill_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (c000000000eaa080)
Location: net/rfkill/core.c:308
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
c000000000eaa080-c000000000eaa280: rfkill_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffe00089e71c)
Location: net/rfkill/core.c:308
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
ffffffe00089e71c-ffffffe00089e834: rfkill_set_block (STB_LOCAL)
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
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81a3b220)
Location: net/rfkill/core.c:308
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
ffffffff81a3b220-ffffffff81a3b36b: rfkill_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff819f7e40)
Location: net/rfkill/core.c:308
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
ffffffff819f7e40-ffffffff819f7f8b: rfkill_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81aa70d0)
Location: net/rfkill/core.c:308
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
ffffffff81aa70d0-ffffffff81aa721b: rfkill_set_block (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rfkill_set_block(struct rfkill *rfkill, bool blocked);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81ab3470)
Location: net/rfkill/core.c:308
Inline: False
Direct callers:
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_fop_write
  - net/rfkill/core.c:rfkill_sync_work
  - net/rfkill/core.c:state_store
  - net/rfkill/core.c:soft_store
  - net/rfkill/core.c:rfkill_epo
  - net/rfkill/core.c:__rfkill_switch_all
```
**Symbols:**

```
ffffffff81ab3470-ffffffff81ab35bb: rfkill_set_block (STB_LOCAL)
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
