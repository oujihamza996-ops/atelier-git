def moyenne(notes):
    return sum(notes) / len(notes)
def note_max(notes):
    return max(notes)
def note_min(notes):
    return min(notes)

notes = [12, 15, 9, 18]
print("Moyenne :", moyenne(notes))
print("Note maximale :", note_max(notes))
print("minimum :",minimum(notes))
