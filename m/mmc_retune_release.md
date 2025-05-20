# Function: <code>mmc_retune_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff816c21c0)
Location: drivers/mmc/core/host.c:93
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_start_req
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff816c21c0-ffffffff816c21f0: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81724ee8)
Location: drivers/mmc/core/host.c:116
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_req
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff81724f40-ffffffff81724f70: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81757e68)
Location: drivers/mmc/core/host.c:116
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_req
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff81757ec0-ffffffff81757ef0: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81776128)
Location: drivers/mmc/core/host.c:114
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_areq
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_start_bkops
  - drivers/mmc/core/mmc_ops.c:mmc_start_bkops
  - drivers/mmc/core/mmc_ops.c:mmc_stop_bkops
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff81775df0-ffffffff81775dfd: mmc_retune_release.part.6 (STB_LOCAL)
ffffffff81776180-ffffffff817761a4: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff817ec498)
Location: drivers/mmc/core/host.c:114
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_start_areq
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_stop_bkops
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff817ec080-ffffffff817ec08d: mmc_retune_release.part.4 (STB_LOCAL)
ffffffff817ec090-ffffffff817ec0b4: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81835681)
Location: drivers/mmc/core/host.c:114
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_stop_bkops
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff81835270-ffffffff8183527d: mmc_retune_release.part.4 (STB_LOCAL)
ffffffff81835280-ffffffff818352a4: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81861631)
Location: drivers/mmc/core/host.c:114
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
```
**Symbols:**

```
ffffffff81861220-ffffffff8186122d: mmc_retune_release.part.4 (STB_LOCAL)
ffffffff81861230-ffffffff81861254: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff818a5361)
Location: drivers/mmc/core/host.c:111
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_retune_release
```
**Symbols:**

```
ffffffff818a54da-ffffffff818a54f3: mmc_retune_release.part.0 (STB_LOCAL)
ffffffff818a54f3-ffffffff818a54fd: mmc_retune_release.cold (STB_LOCAL)
ffffffff818a4f40-ffffffff818a4f62: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff818d77e1)
Location: drivers/mmc/core/host.c:111
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_retune_release
```
**Symbols:**

```
ffffffff818d73b0-ffffffff818d73bd: mmc_retune_release.part.0 (STB_LOCAL)
ffffffff818d73c0-ffffffff818d73e4: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff819aa141)
Location: drivers/mmc/core/host.c:111
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/mmc.c:mmc_sleep
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_retune_release
```
**Symbols:**

```
ffffffff819aa070-ffffffff819aa092: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff819acd8d)
Location: drivers/mmc/core/host.c:113
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/mmc.c:mmc_sleep
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_retune_release
```
**Symbols:**

```
ffffffff819acc50-ffffffff819acc72: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff819915a1)
Location: drivers/mmc/core/host.c:152
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_retune_release
```
**Symbols:**

```
ffffffff81991230-ffffffff81991252: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81a3cd51)
Location: drivers/mmc/core/host.c:170
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_retune_release
```
**Symbols:**

```
ffffffff81a3bfa0-ffffffff81a3bfc2: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81ba9e11)
Location: drivers/mmc/core/host.c:170
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_retune_release
```
**Symbols:**

```
ffffffff81ba8fb0-ffffffff81ba8fe2: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81d4ccb1)
Location: drivers/mmc/core/host.c:170
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_retune_release
```
**Symbols:**

```
ffffffff81d4bc30-ffffffff81d4bc62: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81db7611)
Location: drivers/mmc/core/host.c:170
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_retune_release
```
**Symbols:**

```
ffffffff81db64d0-ffffffff81db6502: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff81e6fae1)
Location: drivers/mmc/core/host.c:169
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:mmc_sanitize
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio.c:mmc_sdio_resume
  - drivers/mmc/core/sdio_io.c:sdio_retune_release
```
**Symbols:**

```
ffffffff81e6e970-ffffffff81e6e9a2: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/host.c (ffff800010b31b6c)
Location: drivers/mmc/core/host.c:111
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_retune_release
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_fix_state
```
**Symbols:**

```
ffff800010b316e8-ffff800010b31704: mmc_retune_release.part.0 (STB_LOCAL)
ffff800010b31708-ffff800010b3174c: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/host.c (c0c0c7cc)
Location: drivers/mmc/core/host.c:111
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_retune_release
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_fix_state
```
**Symbols:**

```
c0c0c3a4-c0c0c3d4: mmc_retune_release.part.0 (STB_LOCAL)
c0c0c3d4-c0c0c408: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/host.c (c000000000c2ba0c)
Location: drivers/mmc/core/host.c:111
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_retune_release
```
**Symbols:**

```
c000000000c2b480-c000000000c2b490: mmc_retune_release.part.0 (STB_LOCAL)
c000000000c2b490-c000000000c2b4c4: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/host.c (ffffffe00070a560)
Location: drivers/mmc/core/host.c:111
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_retune_release
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_issue_rq
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_mq_rw_recovery
  - drivers/mmc/core/block.c:mmc_blk_fix_state
```
**Symbols:**

```
ffffffe00070a132-ffffffe00070a14e: mmc_retune_release.part.0 (STB_LOCAL)
ffffffe00070a14e-ffffffe00070a18c: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff8187b1a1)
Location: drivers/mmc/core/host.c:111
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_retune_release
```
**Symbols:**

```
ffffffff8187ad70-ffffffff8187ad7d: mmc_retune_release.part.0 (STB_LOCAL)
ffffffff8187ad80-ffffffff8187ada4: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff818cc641)
Location: drivers/mmc/core/host.c:111
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_retune_release
```
**Symbols:**

```
ffffffff818cc210-ffffffff818cc21d: mmc_retune_release.part.0 (STB_LOCAL)
ffffffff818cc220-ffffffff818cc244: mmc_retune_release (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void mmc_retune_release(struct mmc_host *host);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/host.c (ffffffff818e9161)
Location: drivers/mmc/core/host.c:111
Inline: True
Inline callers:
  - drivers/mmc/core/host.c:mmc_retune_disable
Direct callers:
  - drivers/mmc/core/core.c:mmc_do_erase
  - drivers/mmc/core/core.c:mmc_cqe_recovery
  - drivers/mmc/core/core.c:mmc_wait_for_req_done
  - drivers/mmc/core/host.c:mmc_retune_disable
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc.c:_mmc_suspend
  - drivers/mmc/core/mmc_ops.c:__mmc_switch
  - drivers/mmc/core/sdio_io.c:sdio_retune_release
```
**Symbols:**

```
ffffffff818e8d30-ffffffff818e8d3d: mmc_retune_release.part.0 (STB_LOCAL)
ffffffff818e8d40-ffffffff818e8d64: mmc_retune_release (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
