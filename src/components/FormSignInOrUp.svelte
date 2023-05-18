<form action="">
    <div class="card flex-shrink-0 w-full max-w-sm shadow-2xl bg-base-100">
        <div class="card-body">
            <h1>Inicio de sesión</h1>
            <div class="form-control">
                <label class="label" for="email">
                    <span class="label-text">Email</span>
                </label>
                <input type="text" placeholder="email" class="input input-bordered" name="email" id="email" />
            </div>
            <div class="form-control">
                <label class="label" for="password">
                    <span class="label-text">Password</span>
                </label>
                <input
                    type="password"
                    placeholder="password"
                    class="input input-bordered"
                    name="password"
                    id="password"
                />
                <label class="label" for="">
                    <!-- svelte-ignore a11y-invalid-attribute -->
                    <button type="button" class="label-text-alt link link-hover"
                        >Aun no estas registrado, Registrate</button
                    >
                </label>
            </div>
            <div class="form-control mt-6">
                <button type="submit" class="btn btn-primary">Login</button>
            </div>
        </div>
    </div>
    
</form>