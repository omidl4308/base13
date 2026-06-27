# base13
{
  "task": "Professional Character Identity Analysis",
  "version": "1.0",
  "objective": "Extract a complete identity sheet from the reference image with maximum facial consistency for future AI image and video generation.",
  "output_format": {
    "language": "English",
    "style": "Technical, objective, highly detailed"
  },
  "analysis": {
    "identity_summary": true,

    "face_shape": {
      "overall_shape": true,
      "face_length_width_ratio": true,
      "forehead_width": true,
      "cheekbone_width": true,
      "jaw_width": true,
      "chin_shape": true,
      "jaw_angle": true,
      "facial_symmetry": true
    },

    "forehead": {
      "height": true,
      "width": true,
      "hairline_shape": true,
      "temple_structure": true
    },

    "eyes": {
      "eye_shape": true,
      "eye_size": true,
      "eye_spacing": true,
      "eye_depth": true,
      "eyelid_type": true,
      "double_eyelid": true,
      "eyelashes": true,
      "iris_color": true,
      "pupil_ratio": true,
      "catchlight_position": true,
      "outer_corner_angle": true,
      "inner_corner_shape": true,
      "lower_eyelid_curve": true
    },

    "eyebrows": {
      "shape": true,
      "thickness": true,
      "density": true,
      "arch": true,
      "length": true,
      "spacing": true,
      "tail_direction": true
    },

    "nose": {
      "bridge_height": true,
      "bridge_width": true,
      "nasal_tip": true,
      "nostril_shape": true,
      "nostril_width": true,
      "nose_length": true,
      "nose_projection": true,
      "nose_angle": true
    },

    "lips": {
      "upper_lip_thickness": true,
      "lower_lip_thickness": true,
      "lip_width": true,
      "cupid_bow": true,
      "mouth_corner_angle": true,
      "philtrum_length": true,
      "lip_texture": true
    },

    "mouth": {
      "mouth_width": true,
      "teeth_visibility": true,
      "neutral_expression": true
    },

    "chin": {
      "projection": true,
      "height": true,
      "width": true,
      "cleft": true
    },

    "jaw": {
      "jawline_definition": true,
      "mandible_angle": true,
      "jaw_contour": true
    },

    "ears": {
      "size": true,
      "position": true,
      "lobe_shape": true
    },

    "skin": {
      "skin_tone": true,
      "undertone": true,
      "texture": true,
      "pores": true,
      "freckles": true,
      "moles": true,
      "scars": true,
      "wrinkles": true
    },

    "hair": {
      "color": true,
      "length": true,
      "density": true,
      "texture": true,
      "parting": true,
      "hairline": true
    },

    "facial_hair": {
      "beard": true,
      "mustache": true,
      "density": true,
      "shape": true
    },

    "head": {
      "head_shape": true,
      "head_proportion": true,
      "neck_length": true,
      "neck_width": true
    },

    "measurements": {
      "golden_ratio_estimation": true,
      "facial_landmarks": true,
      "68_point_landmark_description": true,
      "proportional_ratios": true,
      "distance_between_features": true
    },

    "camera": {
      "camera_angle": true,
      "head_rotation": true,
      "pitch": true,
      "yaw": true,
      "roll": true,
      "lens_estimation": true,
      "lighting_direction": true
    },

    "identity_lock": {
      "distinctive_features": true,
      "non_changeable_features": true,
      "critical_identity_markers": true,
      "consistency_priority_order": true
    }
  },

  "final_output": {
    "master_character_sheet": true,
    "stable_diffusion_prompt": true,
    "flux_prompt": true,
    "midjourney_prompt": true,
    "veo_prompt": true,
    "runway_prompt": true,
    "identity_lock_prompt": true,
    "negative_prompt": true
  },

  "requirements": [
}
