# Patch Tracking: delegate lliang / tim609

Generated from `git-pw patch list --delegate <name>`. Status to be filled in
after checking each thread with `b4` for Reviewed-by/Acked-by/Tested-by/Fixes
tags.

Legend: REVIEWED = has Reviewed-by or Acked-by covering current version and no
unresolved review comments. NEEDS-REVIEW = no such tag yet / tag only on an
older version / review comments outstanding.

## Delegate: lliang

| Series | PW IDs | Subject | Status | Notes |
|---|---|---|---|---|
| mpxy | 2268374,2268375,2268376 | riscv: SBI MPXY core interface + RPMI driver + enable (3 patches) | NEEDS-REVIEW | Dead-code concern on readattr() raised by Charles Perry, unresolved. Review drafted: review-comments/mpxy-series.mbox |

## Delegate: tim609

| Series | PW IDs | Subject | Status | Notes |
|---|---|---|---|---|
| cv1800b-rtc-v2 | 2316760,2316761,2316762 | rtc/sysreset: cv1800b RTC-backed reset (v2, 3 patches) | NEEDS-REVIEW | No Reviewed-by/Acked-by on v2. Review drafted: review-comments/cv1800b-rtc-sysreset-v2.mbox |
| clk-spacemit-mux-v3 | 2316432 | clk: spacemit: program the mux when setting a mix clock's rate (v3) | REVIEWED | Reviewed-by: Yixun Lan <dlan@kernel.org> (DKIM verified), carried from v2. Applied to main (093b0bf6ec3). |
| riscv-spacemit-ddr | 2316431 | riscv: spacemit: handle overlapping DDR firmware relocation | NEEDS-REVIEW | No review tags. Review drafted: review-comments/riscv-spacemit-ddr-overlap.mbox |
| mpfs-serial | 2316076 | board: microchip: mpfs_generic: Allow serial number read failures | NEEDS-REVIEW | No review tags. Review drafted: review-comments/mpfs-generic-serial.mbox |
| spacemit-k3-v3 | 2315434,2315433,2315435,2315436 | board/riscv/configs/doc: SpacemiT K3 Pico-ITX (v3, 4 patches) | SPLIT | Patches 1-3/4: Reviewed-by E Shattow (DKIM verified), applied to main (9175055bac9, a13fd0fdb23, bffece0c08c). Patch 4/4 (doc): NEEDS-REVIEW, wording issue unresolved, review drafted: review-comments/spacemit-k3-doc-v3-4of4.mbox |
| spacemit-k1-spl | 2315364,2315366 (RESEND dup: 2315368,2315369) | spacemit: k1: SPL boot device fallback / no PMIC-SPI requirement (2 patches) | NEEDS-REVIEW | No Reviewed-by/Acked-by on original or RESEND. Review drafted: review-comments/spacemit-k1-spl-resend.mbox |
| pci-spacemit | 2315351,2315357,2315356,2315358,2315359,2315360,2315361,2315362,2315363 | pci: spacemit: controller bring-up fixes (9 patches) | NEEDS-REVIEW | No review tags on any of the 9 patches. Review drafted: review-comments/pci-spacemit-series.mbox |
| phy-spacemit-k1 | 2315348,2315373,2315371,2315386,2315374,2315349,2315350 | phy: spacemit: k1: combo PHY fixes (7 patches) | NEEDS-REVIEW | No review tags; author reported testing on OrangePi R2S in thread. Review drafted: review-comments/phy-spacemit-k1-series.mbox |
| gpio-k3-v1 | n/a (2290316) | gpio: spacemit: add support for K3 SoC | REVIEWED | Acked-by E Shattow (DKIM verified). Applied to main (b5abae6176a). |
| ipi-fix-v1 | n/a (2298060) | riscv: Fix IPI not initialized in riscv_cpu_setup() | REVIEWED | Acked-by Michal Simek + Reviewed-by Yao Zi, Leo Yu-Chi Liang (DKIM verified). Applied to main (e88d8a67f90). |
| maintainers-riscv-v2 | n/a (2300819) | MAINTAINERS: Make RISC-V entry cover all paths containing the keyword | REVIEWED | Reviewed-by Tom Rini + Leo Yu-Chi Liang (DKIM verified). Applied to main (42d8d7fca7d). |
| timer-mmode-v5 | n/a (2302804) | riscv: timer: early timer for M-mode (2 patches) | REVIEWED | Reviewed-by Yao Zi (DKIM verified). Applied to main (75700ceea21, 621349de8e5). |
| fixcmo-v1 | n/a (2308162) | riscv: thead: fix D-cache flushing | REVIEWED | Reviewed-by Yao Zi (DKIM verified). Applied to main (a77d1000431). |
| jh7110-doc | n/a (2310596) | doc: board: starfive: update jh7110 build output description | REVIEWED | Reviewed-by Leo Yu-Chi Liang (DKIM verified). Applied to main (0ae71aec138). |
| mt2824-v1 | 2315212 series (10 patches) | riscv: metanoia: Add support for the MT5824 EVB platform | NEEDS-REVIEW | Only patch 4/10 reviewed (Tom Rini); rest untagged. Review drafted: review-comments/metanoia-mt2824-v1.mbox |
| k1-emac-v1 | 2315079 (3 patches) | net: k1: add Ethernet MAC driver | NEEDS-REVIEW | No tags; does not apply cleanly (conflicts). Review drafted: review-comments/spacemit-k1-emac.mbox |
| 256m-fixes-v1 | 2314060 (2 patches) | riscv: cpu: cv1800b: keep U-Boot out of reserved memory | NEEDS-REVIEW | No tags. Review drafted: review-comments/milkv-duo-256m-boot-fixes.mbox |
| milkv-duo-bootstd-v1 | 2313574 (3 patches) | board: sophgo: milkv_duo: add environment for standard boot | NEEDS-REVIEW | No tags; does not apply cleanly. Review drafted: review-comments/milkv-duo-bootstd.mbox |
| rv32-posix-types-v1 | 2312760 | riscv: restore ILP32 size types on RV32 | NEEDS-REVIEW | No tags. Review drafted: review-comments/riscv-rv32-posix-types.mbox |
| milkv-duo-upstream-dts-v5 | 2312080 (10 patches) | clk/mmc/dt-bindings/riscv: Milk-V Duo 256M upstream devicetree | REVIEWED (blocked) | Reviewed-by Yao Zi + Hiago De Franco on all 10 (DKIM verified), but does NOT apply cleanly to current tree (conflict in dts/upstream/Bindings/soc/sophgo/sophgo.yaml). Not applied; needs rebase by author. |
| k3-ethernet-support-v1 | 2310547 (2 patches) | net: dwc_eth_qos: spacemit: add support for K3 SoC | NEEDS-REVIEW | Only Tested-by (no Reviewed-by/Acked-by); does not apply cleanly. Review drafted: review-comments/spacemit-k3-ethernet.mbox |
| k3-pinctrl-support-v2 | 2310141 (2 patches) | pinctrl: spacemit: k3: add K3 pin support | NEEDS-REVIEW | Patch 2/2 Acked-by E Shattow; patch 1/2 untagged; does not apply cleanly. Review drafted: review-comments/spacemit-k3-pinctrl.mbox |
| k3-clock-reset-support-v2 | 2310051 (8 patches) | clk/reset: spacemit: K3 clock tree + reset driver | REVIEWED (blocked) | Acked-by E Shattow on all 8 (DKIM verified), but does NOT apply cleanly to current tree. Not applied; needs rebase by author. |
| spacemit-aihd-v3 | 2308876 (2 patches) | tools/doc: SpacemiT K3 boot image (mkimage + docs) | REVIEWED (blocked) | Reviewed-by Yao Zi, Yixun Lan, E Shattow (DKIM verified), but does NOT apply cleanly to current tree. Not applied; needs rebase by author. |
| mpfs-kconfig-move | 2306927,2306929,2306930 (series 523985) | riscv: mpfs: move system controller configs to CPU Kconfig | NEEDS-REVIEW | No tags, no patchwork comments. b4 404s on this thread; patches fetched via `git-pw patch download`. Review drafted: review-comments/mpfs-kconfig-restructure.mbox |
| m4-v13 | 2303527 (7 patches) | spacemit: k1: boot device selection / SD/eMMC in SPL | REVIEWED (blocked) | Tested-by + Reviewed-by Yixun Lan on all 7 (DKIM verified), but does NOT apply cleanly to current tree. Not applied; needs rebase by author. |
| spacemit-custodian-v1 | 2300270 | MAINTAINERS: add new SpacemiT custodians | REVIEWED (blocked) | Reviewed-by Yao Zi + Tom Rini (DKIM verified), but conflicts against MAINTAINERS after other applies in this session. Not applied; needs rebase. |
| k1-pinctrl-v2 | 2299216 (2 patches) | pinctrl: k1: add IO power domain configuration support | NEEDS-REVIEW | No tags. Review drafted: review-comments/spacemit-k1-pinctrl-fixes.mbox |
| mpfs-coreqspi | 2298711 | riscv: mpfs: imply the CoreQSPI driver | NEEDS-REVIEW | No tags despite applying cleanly. Review drafted: review-comments/mpfs-coreqspi-fix.mbox |
| riscv-net-boot-v1 | 2298062 | arch/riscv: Allow booting from NET | NEEDS-REVIEW | No tags. Review drafted: review-comments/riscv-net-boot-option.mbox |
| mpxy-rpmi-v3 | 2296704 (5 patches) | firmware/drivers: rpmi: SBI MPXY transport + mpxy command | NEEDS-REVIEW | No tags. Review drafted: review-comments/rpmi-sbi-mpxy-transport.mbox |
| riscv-full-fit-v2 | 2296382 (6 patches) | spl: fit: full FIT / loadables support | NEEDS-REVIEW | No tags; does not apply cleanly. Review drafted: review-comments/riscv-full-fit-support.mbox |
| mpfs-fpga-info-v3 | 2293685 | riscv: mpfs: Read and store FPGA design information | NEEDS-REVIEW | No tags despite v3, applies cleanly. Review drafted: review-comments/mpfs-fpga-design-info.mbox |
| riscv-iommu-v2 | 2291958 | iommu: Add RISC-V IOMMU driver | NEEDS-REVIEW | No tags; does not apply cleanly. Review drafted: review-comments/riscv-iommu-driver.mbox |
| k1-m1x-tlv | 2291834 | board: spacemit: k1: accept the "m1-x_" TLV product name prefix | REVIEWED (blocked) | Reviewed-by Yixun Lan (DKIM verified), but conflicts against board/spacemit/k1/spl.c after other applies in this session. Not applied; needs rebase. |
| p8700-v7 | 2224452 (7 patches) | riscv: p8700: Coherence Manager (CM) and IOCU support | NEEDS-REVIEW | No tags despite v7 (7th revision, zero reviewer engagement). Review drafted: review-comments/p8700-cm-iocu-v7.mbox |

## Summary

**Applied to main (11 patches total, chronological order):**
1. `9175055bac9` board: spacemit: add SpacemiT K3 Pico-ITX
2. `a13fd0fdb23` riscv: dts: spacemit: k3: add binman node
3. `bffece0c08c` configs: spacemit: Add K3 default configuration
4. `093b0bf6ec3` clk: spacemit: program the mux when setting a mix clock's rate
5. `b5abae6176a` gpio: spacemit: add support for K3 SoC
6. `e88d8a67f90` riscv: Fix IPI not initialized in riscv_cpu_setup()
7. `42d8d7fca7d` MAINTAINERS: Make RISC-V entry cover all paths containing the keyword
8. `75700ceea21` riscv: timer: Make RISCV_TIMER definitions weak
9. `621349de8e5` riscv: timer: Enable early timer for M-mode
10. `a77d1000431` riscv: thead: fix D-cache flushing
11. `0ae71aec138` doc: board: starfive: update jh7110 build output description

**REVIEWED but blocked (has Reviewed-by/Acked-by, but does NOT apply cleanly to current tree — needs author rebase, not applied):**
- milkv-duo-upstream-dts-v5 (PW 2312080, 10 patches)
- k3-clock-reset-support-v2 (PW 2310051, 8 patches)
- spacemit-aihd-v3 (PW 2308876, 2 patches)
- m4-v13 spacemit k1 boot device (PW 2303527, 7 patches)
- spacemit-custodian-v1 (PW 2300270, 1 patch)
- k1-m1x-tlv (PW 2291834, 1 patch)

**Review comments drafted (24 mbox files in `review-comments/`), pending user review before sending:**
- `mpxy-series.mbox`
- `cv1800b-rtc-sysreset-v2.mbox`
- `riscv-spacemit-ddr-overlap.mbox`
- `mpfs-generic-serial.mbox`
- `spacemit-k3-doc-v3-4of4.mbox`
- `spacemit-k1-spl-resend.mbox`
- `pci-spacemit-series.mbox`
- `phy-spacemit-k1-series.mbox`
- `metanoia-mt2824-v1.mbox`
- `spacemit-k1-emac.mbox`
- `milkv-duo-256m-boot-fixes.mbox`
- `milkv-duo-bootstd.mbox`
- `riscv-rv32-posix-types.mbox`
- `spacemit-k3-ethernet.mbox`
- `spacemit-k3-pinctrl.mbox`
- `mpfs-kconfig-restructure.mbox`
- `spacemit-k1-pinctrl-fixes.mbox`
- `mpfs-coreqspi-fix.mbox`
- `riscv-net-boot-option.mbox`
- `rpmi-sbi-mpxy-transport.mbox`
- `riscv-full-fit-support.mbox`
- `mpfs-fpga-design-info.mbox`
- `riscv-iommu-driver.mbox`
- `p8700-cm-iocu-v7.mbox`

## Next steps
1. For each series, run `b4 am`/`b4 mbox` (or `git-pw patch show`) on the
   thread to check for Reviewed-by / Acked-by / Tested-by / Fixes tags.
2. Classify each series as REVIEWED or NEEDS-REVIEW.
3. REVIEWED series: apply to master in chronological order (oldest first).
4. NEEDS-REVIEW series: write review comments as an mbox-format reply for
   the user to inspect before sending.
