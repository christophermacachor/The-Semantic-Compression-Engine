function cat(t):
    if not decidable(t):
        return U

    if irreducible(t):
        return C0

    if names_operation_from_C0(t):
        return C1

    if recoverable_structure(t):
        return C2

    if encoding_of_C3(t):
        return C4

    return C3
