<script>
    import {
        Table,
        TableBody,
        TableBodyCell,
        TableBodyRow,
        TableHead,
        TableHeadCell,
        Checkbox,
    } from "flowbite-svelte";
</script>

<Table>
    <TableHead>
        <TableHeadCell class="!p-4">
            <Checkbox />
        </TableHeadCell>
        <TableHeadCell>Producto</TableHeadCell>
        <TableHeadCell>Tipo</TableHeadCell>
        <TableHeadCell>Disponible</TableHeadCell>
        <TableHeadCell>Precio</TableHeadCell>
        <TableHeadCell>Peso</TableHeadCell>
        <TableHeadCell>acciones</TableHeadCell>
    </TableHead>
    <TableBody class="divide-y">
        <TableBodyRow>
            <TableBodyCell class="!p-4">
                <Checkbox />
            </TableBodyCell>
            <TableBodyCell>Tres Leches Personal</TableBodyCell>
            <TableBodyCell>Tres leches</TableBodyCell>
            <TableBodyCell>Si</TableBodyCell>
            <TableBodyCell>L 33</TableBodyCell>
            <TableBodyCell>240 gramos</TableBodyCell>
            <TableBodyCell>
                <a
                    href="/tables"
                    class="font-medium text-primary-600 hover:underline dark:text-primary-500"
                    >Editar</a
                >
                <a
                    href="/tables"
                    class="font-medium text-red-600 hover:underline dark:text-red-500"
                    >Remover</a
                >
            </TableBodyCell>
        </TableBodyRow>
        <TableBodyRow>
            <TableBodyCell class="!p-4">
                <Checkbox />
            </TableBodyCell>
            <TableBodyCell>Tres Leches Redondo</TableBodyCell>
            <TableBodyCell>Tres leches</TableBodyCell>
            <TableBodyCell>Si</TableBodyCell>
            <TableBodyCell>L 44</TableBodyCell>
            <TableBodyCell>240 gramos</TableBodyCell>
            <TableBodyCell>
                <a
                    href="/tables"
                    class="font-medium text-primary-600 hover:underline dark:text-primary-500"
                    >Editar</a
                >
                <a
                    href="/tables"
                    class="font-medium text-red-600 hover:underline dark:text-red-500"
                    >Remover</a
                >
            </TableBodyCell>
        </TableBodyRow>
        <TableBodyRow>
            <TableBodyCell class="!p-4">
                <Checkbox />
            </TableBodyCell>
            <TableBodyCell>Tres Leches 15 porciones</TableBodyCell>
            <TableBodyCell>Tres leches</TableBodyCell>
            <TableBodyCell>Si</TableBodyCell>
            <TableBodyCell>L 100</TableBodyCell>
            <TableBodyCell>240 gramos</TableBodyCell>
            <TableBodyCell>
                <a
                    href="/tables"
                    class="font-medium text-primary-600 hover:underline dark:text-primary-500"
                    >Editar</a
                >
                <a
                    href="/tables"
                    class="font-medium text-red-600 hover:underline dark:text-red-500"
                    >Remover</a
                >
            </TableBodyCell>
        </TableBodyRow>
    </TableBody>
</Table>
