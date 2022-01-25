<template>
    <div>
        <TheHeader />
        <main class="tc">
            <slot name="header" />
            <div>
                <slot />
            </div>
            <slot name="footer" />
        </main>
        <TheFooter />
    </div>
</template>

