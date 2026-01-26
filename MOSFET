# Projet : Simulation de courant MOSFET (BTS)
# Auteur : Rayan144218

def calculer_id(vgs, vth, k):
    """
    Calcule le courant de drain Id en régime de saturation.
    Formule : Id = k * (Vgs - Vth)^2
    """
    if vgs < vth:
        return 0
    else:
        return k * (vgs - vth)**2

# --- Paramètres de test ---
v_threshold = 2.0  # Tension de seuil en Volts
gain_k = 0.5       # Constante liée au composant
v_gate_source = 5.0

courant = calculer_id(v_gate_source, v_threshold, gain_k)
print(f"Le courant Id pour Vgs={v_gate_source}V est de {courant}A")
