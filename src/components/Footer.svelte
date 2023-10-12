<footer>
    <div>
        <a href=""
        >@{new Date().getFullYear()}
        HEROPY</a>
    </div>
    <a href="http://github.com/HeropyCode/Svelte-Movie-app"
    >Github Repo.</a>
</footer>


<style lang="scss">
    footer {
        padding: 70px;
        text-align: center;
        a {
            color: $color--white-10;
            text-decoration: none;
            &:hover {
                text-decoration: underline;
            }
        }
    }
</style>